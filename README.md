# Health data resources: A collection

### State-hosted resources

[NJSHAD: State Health Assessment Data](https://www26.state.nj.us/doh-shad/)

Has New Jersey health data in two categories: pre-written Indicator reports, and Dataset Queries that allow you to choose variables. It allows for a handful of municipality-level queries, but it's mostly county or state level. Among other topics, it has basic incidence levels of:

* Infant and maternal health parameters
* General mortality and birth rates
* "Behavioral Risk Factors" (based on survey, so not comprehensive)
* Communicable diseases
* Immunizations
* Hospital admission and discharge rates

[Communicable Disease Service](http://nj.gov/health/cd/statistics/)
- Has flu, rabies and other communicable disease reports, premade so not a lot of options or pretty machine-readable formatting
- Has school-level vaccine reports: http://www.nj.gov/health/cd/statistics/imm-status-reports/

[NJ CARES opioid website](http://www.nj.gov/oag/njcares/)
- Working on creating a live updating site of opioid prescriptions and deaths.

- [Hospital reports](http://nj.gov/humanservices/dmhas/publications/hospital/):
Monthly admissions, discharges, and other basic data on state hospitals. As of this writing it's four months behind, though.

- [Various Performance reports](http://www.state.nj.us/health/healthfacilities/reportcards.shtml):
Ranks hospitals in a handful of major areas like heart attacks treatment, as well as nursing homes, renal centers, HMOs and a handful of other types of providers and institutions.

### Federal health resources

#### CDC

- [Data.cdc.gov](https://data.cdc.gov/):
The fairly complete list of data on various topics.

- [National Center for Health Statistics](https://www.cdc.gov/nchs/index.htm)

- [CDC Wonder](https://wonder.cdc.gov/):
 The most powerful query-able database for mortality statistics, yet not super user-friendly. Goes up to county-level data on pretty much every categorized cause of death. Also has 
⋅⋅* AIDS data,
⋅⋅* Environmental variables (like temperature),
⋅⋅* Vaccine adverse reporting data

- [National Notifiable Infectious Disease tables](https://wonder.cdc.gov/nndss/nndss_weekly_tables_menu.asp):
 Certain infectious diseases have reporting requirements. This collects each week's data for every state into a pdf and spreadsheet.

- [Behavioral Risk Factor Surveillance Survey](https://www.cdc.gov/brfss/):
Telephone surveys on health factors and risks, chronic conditions, etc.

- [Injury Statistics Query](https://www.cdc.gov/injury/wisqars/index.html)

- [Disability and Health data system](https://www.cdc.gov/ncbddd/disabilityandhealth/dhds.html)

- [CDC weekly flu report](https://www.cdc.gov/flu/weekly/)

- [Foodborne Outbreak Tracking and reporting](https://wwwn.cdc.gov/foodborneoutbreaks/)

- [Atlas Plus](https://gis.cdc.gov/grasp/nchhstpatlas/charts.html): 
national and some state-level incidence data for AIDS and other STDs. Allows data downloads.

- [OSHdata: Office on Smoking and Health](https://www.cdc.gov/oshdata/): 
one of a variety of datasets the CDC has on tobacco use.

- [Environmental Public Health Tracking Network](https://ephtracking.cdc.gov/DataExplorer/#/):
Look up stats on air quality, asthma, cancers, pesticide exposure and a number of other environmental health variables.

#### CMS

Most CMS data on patients or health use focuses only on Medicare and/or Medicaid patients, however there are definite exceptions, especially if you're willing to dig.

- [Hospital Compare data](https://data.medicare.gov/data/archives/hospital-compare)

- [Data.medicare.gov](https://data.medicare.gov/)

- [Open Payments database](https://www.cms.gov/OpenPayments/index.html):
Find out how much your doctor received from drug and device companies.

- [Medicare Provider Utilization and Payment data](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/index.html): Medicare patient data on 
⋅⋅* Physician visits and utilization,
⋅⋅* Inpatient and Outpatient Services,
⋅⋅* Prescriber data (any drug you'd like to know about, pretty much) -- includes state-wide totals as well as individual doctors
⋅⋅* Home health agencies, skilled nursing facilities and hospice providers: their names and basic patient info

- [Chronic conditions](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Chronic-Conditions/CC_Main.html) prevalence and cost to Medicare 

- [Cost Reports](https://www.cms.gov/Research-Statistics-Data-and-Systems/Downloadable-Public-Use-Files/Cost-Reports/index.html):
LOT of work to parse but has a wealth of data. Every Medicare-certified institution has to send CMS this data that includes the amount they spend on EVERYTHING in the facility and staffing and patient levels. If you're just looking for one institution it might be worth your time to FOIA the pdf rather than have to dig through the oodles of data.

- [Medicare Enrollment Dashboard](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Dashboard/Medicare-Enrollment/Enrollment%20Dashboard.html):
Month-by-month, state-by-state data on Medicare enrollment. There's more detailed and historical data buried in the CMS website as well.

- [National Health Expenditure data](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/NationalHealthExpendData/index.html)

#### Other federal

- [Medical Expenditure Panel Survey](https://meps.ahrq.gov/mepsweb/):
"the most complete source of data on the cost and use of health care and health insurance coverage."

- [Healthcare.gov/Obamacare enrollment data](https://www.healthcare.gov/health-and-dental-plan-datasets-for-researchers-and-issuers/):
Info about plans available on the exchange.

- [openFDA](https://open.fda.gov/):
Mostly on drug histories and adverse events.

- [SAMSHA Mental health data](https://www.samhsa.gov/data/reports-by-geography?tid=650&map=1): 
Has state-by-state estimates of substance use and mental health disorders.

- [Open HIPAA investigations](https://ocrportal.hhs.gov/ocr/breach/breach_report.jsf)

### Third-party data sources

- [County Health Rankings](http://www.countyhealthrankings.org/app/new-jersey/2017/rankings/middlesex/county/outcomes/overall/snapshot):
Somehow supported by the CDC, but run by University of Wisconsin. Allows you to look up a county and compare on health outcomes, behaviors (like obesity) and socioeconomic factors.

- [ProPublica Vital Signs](https://projects.propublica.org/vital-signs/):
Amazing helpful tool for digging through CMS data, including payments and prescriptions. Go here if you're looking for an individual doctor or a handful of them. You can also go to [Dollars for Docs](https://projects.propublica.org/docdollars/)and [Prescriber Checkup](https://projects.propublica.org/checkup/) for a more detailed version.

- [Global Health Data Exchange](http://ghdx.healthdata.org/)

- [Bloomberg health care data compilation](https://github.com/BloombergGraphics/2017-health-insurer-exits-data): 
County-by-county insurance selections and offerings.

- [OECD data](https://data.oecd.org/health.htm): 
Broad, top-level international health data, both conditions and care.

- [Kaiser health data](https://www.kff.org/statedata/): 
Basic state comparisons on a wide range of topics.

- [SIDER](http://sideeffects.embl.de/):
A database of drug side effects.

- [National Electronic Injury Surveillance System](https://www.cpsc.gov/Research--Statistics/NEISS-Injury-Data/):
A survey that tracks injuries from consumer products. Steve used to use this to talk about Christmas-related injuries. 

- [Cancer Statistics Center](https://cancerstatisticscenter.cancer.org/#!/):
Basic tool to track cancer incidence by type and state.

- [Open Food Facts](https://world.openfoodfacts.org/):
A database of nutritional info for food products. Might be helpful as a substitute for your basic Google search.

- [The Health Inequality Project](https://healthinequality.org/data/):
Data on life expectancy and other health outcomes by income, race, and gender.

