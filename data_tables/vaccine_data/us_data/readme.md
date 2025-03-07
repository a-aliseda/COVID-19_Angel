# U.S. States vaccine data

## Files in this folder

- time_series_covid19_vaccine_us.csv: Contains historical data, updated once a week. Each row is uniquely defined by `Province_State`, `Date`, and `UID`. Long format.
- data_dictionary.csv: Metric definitions
- readme.md: This file. Description of contents and list of data sources

## Data source for updates after 9/6/2022
Currently, the only data source for all US vaccine data are the Centers for Disease Control and Prevention (CDC) which update on a weekly basis. Further information about this source is available here: 
- CDC Vaccine Tracker: https://covid.cdc.gov/covid-data-tracker/#vaccinations

## Data sources for updates before 9/6/2022
This composite method of sourcing vaccination metrics is no longer followed by the CRC as of 9/6/2022 and it is explained here for reference purposes.

Our data sources were a combination of the State's public dashboards listed below and the [CDC Vaccine Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations). The logic to combine the data was as follows:
1. If a State was making available a metric, we compared that metric’s value with the metric value provided by the CDC and reported the largest value to reflect the latest reporting of that metric. Note, all metrics are cumulative
2. If a State was not making available a metric, that metric was sourced from the CDC Vaccine Tracker

If total administered doses was not available by State sources, but the different stages of doses (1st, 2nd, etc) were available, the value of total doses administered was determined by summing the stages of doses administered.

The logic was applied each time data was collected. Therefore, for a each State, the source for a given metric’s value may not have been the same for all days. It depended on when the State and the CDC update their respective public data.

### Alaska

- [State dashboard](http://dhss.alaska.gov/dph/epi/id/pages/COVID-19/vaccine.aspx)
- [State COVID-19 Newsroom](https://gov.alaska.gov/home/covid19news/)

### Alabama

- [State dashboard](https://alpublichealth.maps.arcgis.com/apps/opsdashboard/index.html#/e4a232feb1344ce0afd9ac162f3ac4ba)
- [Governor's Newsroom](https://governor.alabama.gov/newsroom/category/press-releases/)

### American Samoa

- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Arkansas

- [State dashboard](https://www.healthy.arkansas.gov/programs-services/topics/covid-19-vaccination-plan)
- [Governor's Newsroom](https://governor.arkansas.gov/news-media/press-releases/)

### Arizona

- [State dashboard](https://www.azdhs.gov/preparedness/epidemiology-disease-control/infectious-disease-epidemiology/covid-19/dashboards/index.php)
- [State vaccine report](https://www.azdhs.gov/documents/preparedness/epidemiology-disease-control/infectious-disease-epidemiology/novel-coronavirus/vaccine-phases.pdf)
- [Governor's Newsroom](https://azgovernor.gov/news-releases)

### California

- [State dashboard](https://covid19.ca.gov/vaccines/#California-vaccines-dashboard)
- [State COVID-19 Vaccine site](https://www.cdph.ca.gov/Programs/CID/DCDC/Pages/COVID-19/VaccineDoses.aspx)
- [State COVID-19 Newsroom](https://covid19.ca.gov/latest-news/)

### Colorado

- [State dashboard](https://covid19.colorado.gov/vaccine-data-dashboard)
- [State COVID-19 Newsroom](https://covid19.colorado.gov/category/press-release?page=0)

### Connecticut

- [Governor's Newsroom](https://portal.ct.gov/Coronavirus/Pages/Governors-Press-Releases)
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Delaware

- [State dashboard](https://myhealthycommunity.dhss.delaware.gov/locations/state/days_to_show/284/primary_trend_type/bar#overview_trends)
- [Governor's Newsroom](https://news.delaware.gov/tag/coronavirus/)

### District of Columbia

- [DC's dashboard](https://coronavirus.dc.gov/data/vaccination)
- [DC's COVID-19 Newsroom](https://coronavirus.dc.gov/newsroom)

### Federal Entities

Federal entities included: Bureau of Prisons, Department of Defense, Indian Health Services, and Veterans Health
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Federated States of Micronesia

- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Florida

- [State vaccine report](https://floridahealthcovid19.gov/)
- [Governor's Newsroom](https://www.flgov.com/2020/12/)

### Georgia

- [State dashboard](https://dph.georgia.gov/covid-vaccine)
- [Governor's Newsroom](https://gov.georgia.gov/press-releases)

### Guam

- [COVID-19 Dashboard](http://dphss.guam.gov/covid-19/)
- [Guam Homeland Security Newsroom](https://ghs.guam.gov/news)

### Hawaii

- [State dashboard](https://health.hawaii.gov/coronavirusdisease2019/what-you-should-know/current-situation-in-hawaii/#vaccine)
- [State COVID-19 Newsroom](https://hawaiicovid19.com/news/)

### Idaho

- [State dashboard](https://coronavirus.idaho.gov/)

### Iowa

- [Vaccine Administration Report](https://idph.iowa.gov/Portals/1/userfiles/61/COVID19%20Vaccine%20Administration.pdf)
- [Governor's Newsroom](https://governor.iowa.gov/newsroom)
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Illinois

- [State vaccine dashboard](http://www.dph.illinois.gov/covid19/vaccinedata?county=Illinois)
- [State COVID-19 Newsroom](https://coronavirus.illinois.gov/s/news)

### Indiana

- [State dashboard](https://www.coronavirus.in.gov/vaccine/2680.htm)
- [Governor's Newsroom](https://www.in.gov/gov/newsroom.htm)

### Kansas

- [Kansas COVID-19 vaccine web page](https://www.kansasvaccine.gov/157/Availability)
- [Weekly Vaccine newsletter](https://www.kansasvaccine.gov/DocumentCenter/View/123/Vaccine-Historical-Document-1721)
- [Governor's Newsroom](https://governor.kansas.gov/newsroom/press-releases/)

### Kentucky

- [State dashboard](https://govstatus.egov.com/ky-covid-vaccine)
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)
- [Governor's Newsroom](https://governor.ky.gov/news)

### Louisiana

- [State dashboard](https://ldh.la.gov/Coronavirus/)
- [Governor's Newsroom](https://gov.louisiana.gov/index.cfm/newsroom/category/9)

### Maine

- [State dashboard](https://www.maine.gov/covid19/vaccines/dashboard)
- [State COVID-19 Newsroom](https://www.maine.gov/covid19/)

### Marshall Islands

- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Maryland

- [State dashboard](https://coronavirus.maryland.gov/#Vaccine)
- [Governor's COVID-19 Newsroom](https://governor.maryland.gov/coronavirus/)

### Massachusetts

- [State weekly vaccination report](https://www.mass.gov/info-details/preparing-for-a-covid-19-vaccine#weekly-covid-19-vaccination-report-)
- [State COVID-19 Newsroom](https://www.mass.gov/lists/press-releases-related-to-covid-19)

### Michigan

- [State dashboard](https://www.michigan.gov/coronavirus/0,9753,7-406-98178_103214_103272-547150--,00.html)

### Minnesota

- [State dashboard](https://mn.gov/covid19/vaccine/data/index.jsp)
- [Governor's Newsroom](https://mn.gov/governor/news/)

### Mississippi

- [State dashboard](https://msdh.ms.gov/msdhsite/_static/14,0,420,976.html)
- [Governor's Newsroom](https://governorreeves.ms.gov/covid-19/#press)

### Missouri

- [State dashboard](https://covidvaccine.mo.gov/data/)
- [Governor's Newsroom](https://governor.mo.gov/press-releases)
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Montana

- [State dashboard](https://montana.maps.arcgis.com/apps/MapSeries/index.html?appid=7c34f3412536439491adcc2103421d4b)
- [State's Department of Health and Human Services newsroom](https://dphhs.mt.gov/AboutUs/News)
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Nebraska

- [State Dashboard](https://experience.arcgis.com/experience/ece0db09da4d4ca68252c3967aa1e9dd/page/page_1/)
- [State COVID-19 Newsroom](http://dhhs.ne.gov/Pages/Coronavirus.aspx)

### Nevada

- [State Dashboard](https://app.powerbigov.us/view?r=eyJrIjoiMjA2ZThiOWUtM2FlNS00MGY5LWFmYjUtNmQwNTQ3Nzg5N2I2IiwidCI6ImU0YTM0MGU2LWI4OWUtNGU2OC04ZWFhLTE1NDRkMjcwMzk4MCJ9)
- [State COVID-19 Newsroom](https://nvhealthresponse.nv.gov/news-resources/press-releases/)
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### New Hampshire

- [State COVID-19 Newsroom](https://www.nh.gov/covid19/news/press-releases.htm)
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### New Jersey

- [COVID-19 Dashboard](https://covid19.nj.gov/#live-updates)
- [State COVID-19 "Vax Matters" Newsletter](https://www.state.nj.us/health/cd/topics/covid2019_vaccination.shtml)

### New Mexico

- [State dashboard](https://cvvaccine.nmhealth.org/public-dashboard.html)

### New York

- [Governor's COVID-19 Newsroom](https://www.governor.ny.gov/keywords/coronavirus)
- [State dashboard](https://covid19vaccine.health.ny.gov/covid-19-vaccine-tracker)

### North Carolina

- [State dashboard](https://covid19.ncdhhs.gov/dashboard/vaccinations)
- [State COVID-19 Newsroom](https://www.nc.gov/covid19/covid19-news-releases)

### North Dakota

- [State Dashboard](https://www.health.nd.gov/covid19vaccine/dashboard)
- [COVID-19 vaccine page](https://www.health.nd.gov/covid-19-vaccine-information)

### Northern Mariana Islands

- [Northern Mariana Islands' COVID-19 dashboard](https://cnmichcc.maps.arcgis.com/apps/opsdashboard/index.html#/4061b674fc964efe84f7774b7979d2b5)
- [Northern Mariana Islands' COVID-19 vaccination program](https://www.vaccinatecnmi.com/covid-19/)
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Ohio

- [State dashboard](https://coronavirus.ohio.gov/wps/portal/gov/covid-19/dashboards/covid-19-vaccine/covid-19-vaccination-dashboard)

### Oklahoma

- [State dashboard](https://oklahoma.gov/covid19.html)

### Oregon

- [State dashboard](https://public.tableau.com/profile/oregon.health.authority.covid.19#!/vizhome/OregonCOVID-19VaccinationTrends/OregonStatewideVaccinationTrends)
- [Governor's Newsroom](https://www.oregon.gov/newsroom/Pages/Agency.aspx?agency=GOV)

### Pennsylvania

- [State dashboard](https://www.health.pa.gov/topics/disease/coronavirus/Pages/Vaccine.aspx)
- [Data file](https://www.health.pa.gov/topics/Documents/Diseases%20and%20Conditions/COVID-19%20Vaccine_Provider%20Locations_Week%201.xlsx)
- [Governor's Newsroom](https://www.governor.pa.gov/newsroom/)
- [COVID-19 vaccine page](https://www.health.pa.gov/topics/disease/coronavirus/Pages/Vaccine.aspx)

### Puerto Rico

- [Governor's Newsroom](https://www.fortaleza.pr.gov/)
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Republic of Palau

- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Rhode Island

- [State dashboard](https://ri-department-of-health-covid-19-data-rihealth.hub.arcgis.com/)
- [Governor's Newsroom](https://www.ri.gov/press/)

### South Carolina

- [State dashboard](https://scdhec.gov/covid19/covid-19-vaccine-allocation)
- [Department of Health and Environmental Control's COVID-19 vaccine web page](https://scdhec.gov/covid19/covid-19-vaccination)
- [Governor's Newsroom](https://governor.sc.gov/news/archive)

### South Dakota

- [State dashboard](https://doh.sd.gov/COVID/Dashboard.aspx)

### Tennessee

- [State vaccination report](https://www.tn.gov/content/dam/tn/health/documents/cedep/novel-coronavirus/Vaccine.pdf)
- [Governor's Newsroom](https://www.tn.gov/governor/news.html)

### Texas

- [State dashboard](https://tabexternal.dshs.texas.gov/t/THD/views/COVID-19VaccineinTexasDashboard/Summary?%3Aorigin=card_share_link&%3Aembed=y&%3AisGuestRedirectFromVizportal=y)

### U.S. Virgin Islands

- [U.S.V.I. COVID-19 Newsroom](https://www.covid19usvi.com/news)
- [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker/#vaccinations)

### Utah

- [State dashboard](https://coronavirus-dashboard.utah.gov/#vaccines)

### Virginia

- [Governor's Newsroom](https://www.governor.virginia.gov/newsroom/news-releases/)

### Vermont

- [Governor's Newsroom](https://governor.vermont.gov/press)

### Washington

- [State COVID-19 Newsroom](https://coronavirus.wa.gov/news)
- [State dashboard](https://www.doh.wa.gov/Emergencies/COVID19/DataDashboard)
- [State vaccination report](https://www.doh.wa.gov/Portals/1/Documents/1600/coronavirus/data-tables/VaccineAdministrationByDateReport.xlsx)

### West Virginia

- [State dashboard](https://health.wyo.gov/publichealth/immunization/wyoming-covid-19-vaccine-information/)
- [State's Department of Health and Human Services newsroom](https://dhhr.wv.gov/COVID-19/pages/updates-and-news.aspx)

### Wisconsin

- [State dashboard](https://www.dhs.wisconsin.gov/covid-19/vaccine-data.htm#day)
- [Governor's Newsroom](https://evers.wi.gov/Pages/Newsroom/Press-Releases.aspx)

### Wyoming

- [Governor's Newsroom](https://governor.wyo.gov/media/news-releases)
- [State web page](https://health.wyo.gov/publichealth/immunization/wyoming-covid-19-vaccine-information/)
