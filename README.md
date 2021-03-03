# Citizen Browser: COVID-19 PSA's

This repository contains code to reproduce the findings featured in our story, "[Official Information About COVID-19 Is Reaching Fewer Black People on Facebook - LINK TK](https://themarkup.org/citizen-browser/)" from our series, [Citizen Browser](https://themarkup.org/citizen-browser/).

Our methodology is described in "[How We Built a Facebook Inspector](https://themarkup.org/citizen-browser/2021/01/05/how-we-built-a-facebook-inspector)".

## Data
The `data/` directory contains three CSV files with data from the story.

`Public-health-agency-view-count.csv` shows the proportion of Citizen Browser panelists from different racial demographics who saw sponsored COVID-19-related posts from any public health agency between December 1 2020 and March 1 2021. 

`HSS-view-count.csv` shows the proportion of panelists who saw sponsored COVID-19-related posts from the U.S. Department of Health and Human Services in this time period.

`Agency-list.csv` contains the list of public health agencies whose posts are included in the data found in `Public-health-agency-view-count.csv`. The agencies are ranked by the number of individual Facebook users in our panel who saw posts from that source.

 The data in the first two files is arranged as follows:

| column              | decription                                                                                     |
|:--------------------|:-----------------------------------------------------------------------------------------------|
| race                | The racial demographic group panelists belong to (self-identified)                             |
| user_view_count     | Number of user accounts from this group exposed to selected public health content              |
| panel_count         | Number of panelists from this group who contributed data to Citizen Browser in the time period |
| percent_demographic | The figure from user_view_count expressed as a percentage of panel_count                       |

## Licensing
Copyright 2021, The Markup News Inc.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
