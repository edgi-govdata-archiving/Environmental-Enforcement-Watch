 [![Code of Conduct](https://img.shields.io/badge/%E2%9D%A4-code%20of%20conduct-blue.svg?style=flat)](https://github.com/edgi-govdata-archiving/overview/blob/master/CONDUCT.md)

# Environmental Enforcement Watch
[Environmental Enforcement Watch](https://www.environmentalenforcementwatch.org/) (EEW) is a project by [EDGI](//envirodatagov.org) to facilitate public interaction with open environmental monitoring data, particularly from EPA's Enforcement and Compliance History Online (ECHO) database.

This repo is the organizational hub of the Github resources associated with EEW.

## EEW Repositories

| Repo | Description | Tools Used |
| ---- | ----------- | ---------- |
| [Environmental-Enforcement-Watch](https://github.com/edgi-govdata-archiving/Environmental-Enforcement-Watch) | **(This Repo!)** Project-wide documentation and issue tracking. | Markdown |
| [EEW_Planning](https://github.com/edgi-govdata-archiving/EEW_Planning)| Project board and issue tracking for the coordination and planning of EEW events. | Markdown |
| [ECHO-Cross-Program](https://github.com/edgi-govdata-archiving/ECHO-Cross-Program) | Jupyter Notebook for examining multiple dimensions of a single EPA-regulated facility.| Python, Jupyter Notebook |
| [ECHO-COVID19](https://github.com/edgi-govdata-archiving/ECHO-COVID19) | Jupyter Notebook for examining the effects of EPA's policy of not enforcing environmental protection rules during the pandemic.| Python, Jupyter Notebook |
| [ECHO-Sunrise](https://github.com/edgi-govdata-archiving/ECHO-Sunrise) | Partnership between EDGI's Environmental Enforcement Watch and Sunrise Boston hubs exploring environmental violations, penalties, and injustices in Massachusetts.| Python, Jupyter Notebook |
| [CD-Report](https://github.com/edgi-govdata-archiving/CD-Report) | R Markdown template for building EEW Report Cards | R, Markdown |
| [ECHO_modules](https://github.com/edgi-govdata-archiving/ECHO_modules) | A repository for code modules that can supplement the Jupyter notebooks. | Python |
| [ECHO-DB-Views](https://github.com/edgi-govdata-archiving/ECHO-DB-Views) | Scripts for setting up and testing views for the ECHO database. Create Views in the database to better prepare the data for use in the Jupyter notebooks.| Python, SQL |
| [ECHO-Geo](https://github.com/edgi-govdata-archiving/ECHO-Geo) | Stores GeoJSON files to support EEW in mapping EPA enforcement and compliance data.| Python |
| [ECHOEPA-to-SQL](https://github.com/edgi-govdata-archiving/ECHOEPA-to-SQL) | Python script "scrapeECHOEPA" that pulls ECHO data and stores it in a mirror. | Python |
  

### EEW Repositories - Not Currently Maintained
| Repo | Description | Tools Used |
| ---- | ----------- | ---------- |
| [ECHO-Hazardous-Waste](https://github.com/edgi-govdata-archiving/ECHO-Hazardous-Waste) | Jupyter Notebooks for ECHO RCRA analysis to use with the EEW events.| Python, Jupyter Notebook |
| [ECHO-Clean-Water-Act](https://github.com/edgi-govdata-archiving/ECHO-CWA-Compliance) | Use EPA's ECHO datasets to view compliance violations by quarter for state/congressional districts. | Python, Jupyter Notebook |
| [ECHO-Clean-Air-Act](https://github.com/edgi-govdata-archiving/ECHO-Air-Violations) | Jupyter Notebook for examining ICIS-AIR_VIOLATION_HISTORY.| Python, Jupyter Notebook |

For more on how all these parts fit together, see [ARCHITECTURE.md](https://github.com/edgi-govdata-archiving/Environmental-Enforcement-Watch/blob/master/ARCHITECTURE.md).

## EEW Notebooks
You can find a list of all our notebooks and links to run them in Google Colab here: https://docs.google.com/spreadsheets/d/1Z2rBoGqb_SXW6oAu12A6TCWEJGV1pk0YxL13P_Z5Wlw/edit#gid=903191621

### Active Notebooks
| Notebook | Description | Tools Used |
| ---- | ----------- | ---------- |
| [ECHO-COVID19.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-COVID19/blob/main/ECHO-COVID19.ipynb) | This notebook tracks how environmental enforcement has decreased as a result of the EPA memo released on March 2020 regarding environmental enforcement during the COVID-19 pandemic. Using this notebook, you can track how facilities' releases—as well as monitoring and reporting—of air and water hazards has changed over the past few months, compared to previous years. |  Python, Jupyter Notebook |
| [ECHO-Cross-Programs.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Cross-Program/blob/master/ECHO-Cross-Programs.ipynb) | This notebook examines data from the EPA's Enforcement and Compliance History Online (ECHO) database (https://echo.epa.gov/). It includes information from EPA's programs covering air quality (the Clean Air Act, or CAA), water quality (the Clean Water Act, or CWA), drinking water (Safe Drinking Water Act, SDWA) and hazardous and other waste processing (the Resource Recovery and Conservation Act, or RCRA). |  Python, Jupyter Notebook |
| [AllPrograms.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Cross-Program/blob/master/AllPrograms.ipynb) | This notebook examines data from the EPA's Enforcement and Compliance History Online (ECHO) database (https://echo.epa.gov/) in order to build EEW Report Cards for congressional districts and states. It includes information from EPA's programs covering air quality (the Clean Air Act, or CAA), water quality (the Clean Water Act, or CWA) and hazardous and other waste processing (the Resource Recovery and Conservation Act, or RCRA). |  Python, Jupyter Notebook |
| [ECHO-National.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Cross-Program/blob/master/ECHO-National.ipynb) | This notebook examines data from the EPA's Enforcement and Compliance History Online (ECHO) database (https://echo.epa.gov/) in order to build a EEW Report Card for the entire US. It includes information from EPA's programs covering air quality (the Clean Air Act, or CAA), water quality (the Clean Water Act, or CWA) and hazardous and other waste processing (the Resource Recovery and Conservation Act, or RCRA). |  Python, Jupyter Notebook |
| [ECHO-Sunrise.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Sunrise/blob/main/ECHO-Sunrise.ipynb) | This notebook examines data from the EPA's Enforcement and Compliance History Online (ECHO) database (https://echo.epa.gov/) in order to build a EEW Report Card for Sunrise Boston. |  Python, Jupyter Notebook |
| [echo-by-zip.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-by-Zip-Code/blob/main/echo-by-zip.ipynb) | This workbook is a way to quickly view data from EPA's Enforcement and Compliance History Online portal that is relevant just to your zip code. It is designed to work with the ECHO Exporter file.| Python, Jupyter Notebook |
| [echo-by-cd.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-by-Zip-Code/blob/main/echo-by-cd.ipynb) | This workbook is a way to quickly view data from EPA's Enforcement and Compliance History Online portal that is relevant just to your congressional district. It is designed to work with the ECHO Exporter file. | Python, Jupyter Notebook |
| [environmental-crime.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Environmental-Crime/blob/main/environmental-crime.ipynb) | This workbook is a way to quickly view data from EPA's Enforcement and Compliance History Online portal that is relevant to your city.The workbook shows you the cost, in dollar terms, of the climate change-causing greenhouse gases industries in your city are allowed to release, and whether enforcement actions are taken against facilities who violate the Clean Air Act. | Python, Jupyter Notebook |
| [ECHO_inspections-enforcement-compliance.ipynb](https://colab.research.google.com/github/ericnost/EDGI/blob/master/ECHO_inspections-enforcement-compliance.ipynb) | This notebook draws on data in ECHO to compare EPA regions in terms of compliance, inspections, and enforcements, across all programs (Clean Water Act, Clean Air Act, and the Resource Conservation and Recovery Act). | Python, Jupyter Notebook |
 

### Inactive Notebooks - Not Currently Maintained
| Notebook | Description | Tools Used |
| ---- | ----------- | ---------- |
| [rcra-enforcements.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Hazardous-Waste/blob/master/rcra-enforcements.ipynb) | This notebook examines ECHO data on oversight of the handling of waste, and hazardous waste in particular, uder the Resource Conservation and Recovery Act, or RCRA. This notebook focuses on formal enforcement cases, when the EPA or state environmental agency moves forward from inspections and findings of violation toward further actions. It uses data from the ECHO downloadable files entitled using ECHO_EXPORTER, RCRA_FACILITIES, and RCRA_ENFORCEMENTS. |  Python, Jupyter Notebook |
| [rcra-inspections.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Hazardous-Waste/blob/master/rcra-inspections.ipynb) | This notebook examines ECHO data on oversight of the handling of waste, and hazardous waste in particular, uder the Resource Conservation and Recovery Act, or RCRA. It uses data from the ECHO downloadable files entitled using ECHO_EXPORTER, RCRA_FACILITIES, and RCRA_EVALUATIONS. |  Python, Jupyter Notebook |
| [rcra-violation.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Hazardous-Waste/blob/master/rcra-violation.ipynb) |  This notebook examines ECHO data on oversight of the handling of waste, and hazardous waste in particular, uder the Resource Conservation and Recovery Act, or RCRA. It uses data from the ECHO downloadable files entitled ECHO_EXPORTER, RCRA_FACILITIES, and RCRA_VIOLATIONS. | Python, Jupyter Notebook |
| [CWA_Inspections.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Clean-Water-Act/blob/master/echo-cwa-compliances-inspections.ipynb) | This notebook examines ECHO data on the National Pollutant Discharge Elimination System, or NPDES, which was established under the Clean Water Act to require monitoring and compliance from wastewater treatment plants, factories, and other point sources of water pollution. This notebook uses ECHO_EXPORTER and NPDES_INSPECTIONS. |  Python, Jupyter Notebook |
| [CWA_Enforcements.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Clean-Water-Act/blob/master/echo-cwa-enforcements.ipynb) | This notebook examines ECHO data on the National Pollutant Discharge Elimination System, or NPDES, which was established under the Clean Water Act to require monitoring and compliance from wastewater treatment plants, factories, and other point sources of water pollution. This notebook uses ECHO_EXPORTER and NPDES_INSPECTIONS. | Python, Jupyter Notebook |
| [all-enforcements.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Clean-Air-Act/blob/master/all-enforcements.ipynb) | This notebook examines ECHO data using CASE_FACILITIES and CASE_ENFORCEMENTS. The CASE_NUMBER FIELD links these two tables. Facilities within the congressional district are identified via the ECHO_EXPORTER data set, with the REGISTRY_ID of ECHO_EXPORTER matched against the same field of CASE_FACILITIES. HQ_DIVISION identifies the program of the enforcement, and CASE_STATUS_DATE is taken to be the date the enforcement was concluded. |  Python, Jupyter Notebook |
| [icis-air-enforcements.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Clean-Air-Act/blob/master/icis-air-enforcements.ipynb) |  This notebook examines ECHO data on formal enforcement cases, the next step after inspections by which the EPA and state agencies move forward to enforce environmental laws. |  Python, Jupyter Notebook |
| [icis-air-inspections.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Clean-Air-Act/blob/master/icis-air-inspections.ipynb) | This notebook examines ECHO data on air inspections, the means by which EPA and state environmental agencies check facilities for their compliance with the Clean Air Act.  | Python, Jupyter Notebook |
| [icis-air-violation.ipynb](https://colab.research.google.com/github/edgi-govdata-archiving/ECHO-Clean-Air-Act/blob/master/icis-air-violation.ipynb) | This notebook examines ECHO data using ICIS-AIR_VIOLATION_HISTORY. It focuses especially on those violations that EPA deems most environmentally concerning, or High Priority Violations" (HPV). To determine the timing of these types of violations, the HPV_DAYZERO_DATE reporting the start date of every episode of High Priority Violation (HPV) is used. The PGM_SYS_ID facility identifier is linked to the ECHO_EXPORTER table's AIR_IDS field for each facility overseen by the EPA under the Clean Air Act. |  Python, Jupyter Notebook |

# Default branch - 'main'
The 'master' branch is no longer the repo's primary branch in line with EDGI's policy decided here: https://github.com/edgi-govdata-archiving/overview/issues/241

> If someone has a local clone, they can update their locals like this:
```
$ git checkout master
$ git branch -m master main
$ git fetch
$ git branch --unset-upstream
$ git branch -u origin/main
$ git symbolic-ref refs/remotes/origin/HEAD refs/remotes/origin/main
```
> The above steps accomplish:
> - Go to the master branch
> - Rename master to main locally
> - Get the latest commits from the server
> - Remove the link to origin/master
> - Add a link to origin/main
> - Update the default branch to be origin/main

(From @jywarren at Public Lab: https://github.com/publiclab/plots2/issues/8077)

--- 

## License & Copyright

Copyright (C) <year> Environmental Data and Governance Initiative (EDGI)
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, version 3.0.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

See the [`LICENSE`](/LICENSE) file for details.
