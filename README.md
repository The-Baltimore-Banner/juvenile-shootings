Baltimore Police Redistricting Analysis
================
 - [Overview](#overview)
 - [Data](#data)
 - [Methodology](#method)
 - [Limitations](#limitations)
 - [License](#license)

## Overview
### More Baltimore juveniles shot in 2022 than any other year

More juveniles have been shot in Baltimore in the first nine months of 2022 than in any other year since 2014. This historically violent year for Baltimore’s children has been fueled by a winter and spring that each had the most young people struck by gunfire since 2014, the earliest year for which there is reliable data. Not only have shootings been more frequent, more juveniles were shot in each shooting than any other year.

The Baltimore Banner has found that the historic violence has been driven by shootings primarily in the city's Eastern police district, a jurisdiction with a relatively small population that has long suffered from high rates of gun violence. Seven other juvenile shootings occurred just outside the district’s borders. City leaders told The Banner that retaliatory gun violence, spats on social media and the flow of illegal "ghost guns" are driving the historic violence. Advocates say pop culture and peer pressure lead to a majority of juvenile shootings to "get backs." Read the story: [Baltimore teenagers are being shot at an alarming rate this year](www.thebaltimorebanner.com/community/criminal-justice/its-hard-watching-so-many-kids-be-gunned-down-baltimore-teenagers-are-being-shot-at-an-alarming-rate-this-year-KDVY2NZXF5F6PODOZFMIVFWCVI/).

Virtually every juvenile shot this year is a Black male. All but one of the 71 juveniles shot are Black. Only eight are female. Juvenile shootings have primarily targeted Black males. Since 2012, only six white juveniles were shot compared to 457 Black juveniles.

<a id="data"></a>
## Data

Note: The crime and victims database is too large to save to GitHub. To execute the code, please download the last [Baltimore Police Part 1 Crimes Database](https://data.baltimorecity.gov/datasets/part-1-crime-data-/explore) and save it in the data folder.

### More juveniles have already been shot in Baltimore in 2022 than any full year since 2014
age_range | 2014 | 2015 | 2016 | 2017 | 2018 | 2019 | 2020 | 2021 | 2020
--- | --- | --- | --- | --- | --- | --- | --- | --- | ---
juvenile | 24 | 62 | 49 | 47 | 47 | 66 | 47 | 62 | 71
18 to 25 | 203 | 331 | 367 | 360 | 267 | 382 | 353 | 286 | 225
26 to 34 | 179 | 315 | 298 | 332 | 342 | 375 | 326 | 337 | 243
35 to 50 | 92 | 169 | 170 | 199 | 224 | 197 | 229 | 283 | 193
51 to 74 | 16 | 45 | 43 | 56 | 66 | 55 | 59 | 54 | 55
NA | 15 | 7 | 9 | 8 | 2 | 3 | 3 | 2 | 8
85 to 100 | NA | 1 | NA | 1 | NA | NA | NA | NA | NA
75 to 84 | NA | NA | NA | NA | 2 | NA | NA | NA | NA

### Nearly 50% more juveniles have been shot in Baltimore during the first nine months of 2022 than in the first nine months of 2021
age_range | 2014 | 2015 | 2016 | 2017 | 2018 | 2019 | 2020 | 2021 | 2020
--- | --- | --- | --- | --- | --- | --- | --- | --- | ---
juvenile | 21 | 50 | 42 | 38 | 35 | 50 | 35 | 48 | 71
18 to 25 | 151 | 258 | 283 | 269 | 206 | 294 | 266 | 190 | 225
26 to 34 | 137 | 232 | 226 | 255 | 254 | 287 | 234 | 252 | 243
35 to 50 | 67 | 126 | 120 | 143 | 149 | 151 | 172 | 214 | 193
51 to 74 | 8 | 36 | 30 | 43 | 49 | 44 | 49 | 40 | 55
age missing | 13 | 4 | 7 | 5 | 2 | 3 | 3 | 2 | 8
85 to 100 | NA | 1 | NA | 1 | NA | NA | NA | NA | NA
75 to 84 | NA | NA | NA | NA | 1 | NA | NA | NA | NA
Total | 397 | 707 | 708 | 754 | 696 | 829 | 759 | 746 | 795

<a id="method"></a>

## Methodology
### How we analyzed BPD violent crime data

This analysis of Open Baltimore Part 1 crime victims database defines shooting victims differently than the Baltimore Police Department. BPD defines shooting victims as someone who was shot, but not killed. This analysis includes both people who were shot and lived, and those who were shot and killed.. It does not include people who were shot at but not wounded. BPD defines that as a “shooting at” crime and does not include it in the Part 1 victim data it releases publicly.

While reviewing this analysis, it is important to focus on the difference between the number of crimes and the number of victims. The data includes one row for every victim of a Part 1 crime. To get distinct crimes, we grouped them by time and location. In some cases, a shooting event led to multiple victims, some who were homicide victims and others who were shooting victims. Our analysis counts this as one shooting crime, but multiple shooting victims.

<a id="limitations"></a>

## Limitations
### Missing entries and errors we overcame to tell this story

This analysis would be better with more data. BPD does not make all crime data available publicly and The Baltimore Banner’s attempts to request this data through a public records request have so far been unsuccessful. There are also known errors in the public data.

In response to questions from The Banner during this analysis, BPD admitted that shooting data before 2014 should not be relied on. As of the date we published this story, they cannot say why. This limitation has caused us to limit our analysis to the year just before and those since Freddie Gray's death, preventing us from examining the impact of the man's death, the protests it spawned and the changes made by the department.

Some entries in the Part 1 Crimes data list impossible ages such as negative numbers or very large numbers. The error is less common in shootings and homicides. There are 52 shooting victims who do not have an age listed or have a negative age. About half of these errors are from years before 2017. The number of ageless victims went up in 2022. There were six recorded ageless victims this year, making up 12% of all ageless victims. All ages that were lower than 0 or higher than 100 were mutated to “NA” to reduce the impact of incorrect ages skewing the mean values of victims per crime.

<a id="license"></a>

## License

Copyright 2022, The Venetoulis Institute for Local Journalism

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
