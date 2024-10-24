# Payments V2 Job Context Message Handler

<img src="https://avatars.githubusercontent.com/u/9841374?s=200&v=4" align="right" alt="UK Government logo">

[![Build Status](https://dev.azure.com/sfa-gov-uk/DCT/_apis/build/status/GitHub/Service%20Fabric/SkillsFundingAgency.das-payments-v2-das-payments-v2-job-context-message-handling?branchName=main)](https://dev.azure.com/sfa-gov-uk/DCT/_apis/build/status/GitHub/Service%20Fabric/SkillsFundingAgency.das-payments-v2-das-payments-v2-job-context-message-handling?branchName=main)
[![Jira Project](https://img.shields.io/badge/Jira-Project-blue)](https://skillsfundingagency.atlassian.net/secure/RapidBoard.jspa?rapidView=782&projectKey=PV2)
[![Confluence Project](https://img.shields.io/badge/Confluence-Project-blue)](https://skillsfundingagency.atlassian.net/wiki/spaces/NDL/pages/3700621400/Provider+and+Employer+Payments+Payments+BAU)
[![License](https://img.shields.io/badge/license-MIT-lightgrey.svg?longCache=true&style=flat-square)](https://en.wikipedia.org/wiki/MIT_License)


## How It Works

The Payments V2 Job Context Message Handler is consumed by the EarningEvents and PeriodEnd services. It is used to monitor and wait for a relevant messages to complete and depending upon job status, will then either delay for a recheck in a given timeframe or report back on job status.

More information here: 
- https://skillsfundingagency.atlassian.net/wiki/spaces/NDL/pages/400130049/4.+Payments+v2+-+Components+DAS+Space
- https://skillsfundingagency.atlassian.net/wiki/spaces/NDL/pages/533856326/a.+Apprenticeship+Earning+Event+DAS+Space

## 🚀 Installation

### Pre-Requisites

* An Azure DevBox configured for Payments V2 development

Setup instructions: https://skillsfundingagency.atlassian.net/wiki/spaces/NDL/pages/950927878/Development+Environment+-+Payments+V2+DAS+Space

### Config

As detailed in: https://skillsfundingagency.atlassian.net/wiki/spaces/NDL/pages/644972941/Developer+Configuration+Settings

Select the configuration for the Earning Events application

## 🔗 External Dependencies

N/A

## Technologies

* .Net Standard 2
* Azure Service Bus

## 🐛 Known Issues

N/A