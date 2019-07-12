## Mapping for ETN's Project Geoserver Layer
The below table shows the columns in OTN's project tables with an example and shows the equivalent column in ETN's project Geoserver layer.

Column in OTN | Example row in OTN | Equivalent in ETN
-- | -- | --
collectioncode | SAMPLE | projectcode
seriescode | OTNGlobal | "ETN"
collaborationtype | Deployment | type
shortname | Sample row | name
longname | Sample row:a row of data | name
citation | Doe, J. Sample Row. 2019 | 
abstract | This is a sample row. | 
institutioncode | INST | 
ocean | NW ATLANTIC | 
country | CANADA | 
state | NOVA SCOTIA | 
local_area | Halifax | 
locality | Dalhousie University | 
westbl | -63.58 | latitude
eastbl | -63.53 | latitude
southbl | 44.48 | longitude
northbl | 44.63 | longitude
status | ongoing | 
usage | null | null
website | http://dal.ca/ | 
sdate | 2008-01-01 | startdate
edate | 2010-05-05  | enddate
node | OTN-Global | "ETN"
database | otn | "ETN"
db_location | db.oceantrack.org | "ETN"
datacentre | Ocean Tracking Network Data Centre, Halifax Canada / otndc@dal.ca | "ETN"
contact_pk | otn123 | (unique identifier of contact)
firstname | John | 
lastname | Doe | 
email | john.doe@dal.ca | 
phone | 123-456-7890 | 
address | 123 Main Street | 
affiliation | DAL | 
ploneid | jdoe | NULL
website | dal.ca | 
orcid | 0123-4567-8901 | 
role | principalInvestigator | 
is_point_of_contact | True | 
datelastmodified | 2019-07-12 | current date
scientificname | Prionace glauca | 
commonname | blue shark | 
aphiaid | 105801 | 
tsn | 160424 | 
taxonstatus | accepted | 
authorityaccepted | accepted | 
aphiaidaccepted | accepted | 
scientificnameaccpt | accepted | 


## Mapping for ETN's Animals/Tags Geoserver Layer
The below table shows the columns in OTN's animal/tag table with an example and shows the equivalent column in ETN's animals/tags Geoserver layer.

Column   in OTN animal | OTN example row | Equivalent in ETN
-- | -- | --
animal_id | Sample | animals.animal_id
tag_type | Acoustic | tags.type
tag_manufacturer | VEMCO | tags.project
tag_model | V9-6L | tags.model
tag_serial_number | 1036912 | tags.serial_number
tag_id_code | 1450 | tags.id_code
tag_code_space | A69-1303 | animals.tag_code_space
tag_implant_type | INTERNAL | animals.implant_type
tag_implant_method | Midventral line incision, 2   sutures | animals.implant_method
tag_activation_date | 2007-03-16T00:00:00 | tags.activation_date
est_tag_life | 90 days | animals.est_tag_life
tagger | JOE RESEARCHER | TBA
tag_owner_pi | JANE RESEARCHER | tags.owner_pi
tag_owner_organization | JANE AND JOE RESEARCH INSTITUTE | tags.owner_organization
common_name_e | CHINOOK | animals.common_name
scientific_name | Oncorhynchus tshawytscha | animals.scientific_name
capture_location | CLEAR CREEK, KOOSKIA NFH | animals.capture_location
capture_latitude | 46.12972 | animals.capture_latitude
capture_longitude | -115.93472 | animals.capture_longitude
wild_or_hatchery | H | animals.wild_or_hatchery
stock | DWORSHAK | animals.stock
length (m) | 0.152 | animals.length
weight (kg) | 0.045 | animals.weight
length_type | FORK | animals.length_type
length2 (m) | 0.2 | animals.length2
length2_type | WIDTH | animals.length2_type
life_stage | JUVENILE | animals.life_stage
age | 7 | animals.age
age_units | months | animals.age_units
sex | M | animals.sex
dna_sample_taken | N | animals.dna_sample_taken
treatment_type | ROR | animals.treatment_type
release_group | 1 | null
release_location | CLEAR CREEK, KOOSKIA NFH | animals.release_location
release_latitude | 46.12972 | animals.release_latitude
release_longitude | -115.93472 | animals.release_longitude
utc_release_date_time | 2007-07-05T22:15:00 | animals.utc_release_date_time
harvest_date | 2007-09-05 | animals.recapture_date
capture_depth (m) | 35 | null
temperature_change (degrees c) | 3.1 | animals.temperature_change
holding_temperature (degrees c) | 10.3 | animals.holding_temperature
preop_hold_period |   | animals.preop_holding_period
postop_hold_period |   | animals.post_op_holding_period
surgery_location | KOOSKIA NATIONAL FISH HATCHERY | animals.surgery_location
date_of_surgery | 2007-11-04T00:00:00 | animals.date_of_surgery
surgery_latitude | 46.12972 | animals.surgery_latitude
surgery_longitude | -115.93472 | animals.surgery_longitude
sedative | TRICAINE METHANESULFONATE | animals.sedative
sedative_concentration (ppm) | 20.0 | animals.sedative_concentration
anaesthetic | TRICAINE METHANESULFONATE | animals.anaesthetic
buffer | SODIUM BICARBONATE | animals.buffer
anaesthetic_concentration (ppm) | 70.0 | animals.anaesthetic_concentration
buffer_concentration_in_anaesthetic (ppm) | 140.0 | animals.buffer_concentration_in_anaesthetic
anaesthetic_concentration_in_recirculation   (ppm) | 50.0 | animals.anesthetic_concentration_in_recirculation
buffer_concentration_in_recirculation   (ppm) | 100.0 | animals.buffer_concentration_in_recirculation
dissolved_oxygen (ppm) | 9.4 | animals.dissolved_oxygen
comments | 146 FL mm; 39.04 WT g; pit tag   not attached; tight fit | animals.comments

## Mapping for ETN's Stations Geoserver Layer
The below table shows the columns in OTN's stations table with an example  and shows the equivalent column in ETN's stations Geoserver layer.

Column in OTN | Example row in OTN | Column in ETN
-- | -- | --
station_name | SMP123 | station_name
otn_array | SAMPLE | collectioncode
station_no | SMP123 | station_name
locality | Dalhousie University | locality
date | 2019-01-01 12:34 | deploy_date
next_proposal_date | null | null
proposal_number | null | null
otn_mission_id | SPL123 | null
intended_lat | 44.65 | stn_lat
intended_long | -63.58 | stn_long
depth_m | 123 |  depth_m
notes | Sample data | null
stationstatus | active | stationstatus

## Mapping for ETN's Deployment Geoserver Layer
The below table shows the columns in OTN's deployment tables with an example and shows the equivalent column in ETN's Deployment Geoserver layer.

Column   in OTN | Example row in OTN | Column in ETN
-- | -- | --
otn_array | SAMPLE | projectcode
station_no | SMP123 | station_name
deploy_date_time | 2019-01-01 12:34:56 | deploy_date_time
deploy_lat | 44.63 | deploy_lat
deploy_long | -63.58 | deploy_long
bottom_depth | 12 | bottom_depth
riser_length | 34 | riser_length
instrument_depth | 56 | instrument_depth
ins_model_no | VR2W | split_part(receiver, '-', 1)
ins_serial_no | 123456 | split_part(receiver, '-', 2)
transmitter | null/A69-1303-12345 |  transmitter
transmit_model | null | model
ar_model_no | PORT MFE |  ar_model_number
ar_serial_no | 12345 |  ar_serial_number
deployed_by | Jane Doe |  receiver_deployed_by
recovered | y |  recovered
recover_date_time | 2019-10-10 12:34:56 | recover_date_time
recover_lat | 44.65 | recover_lat
recover_long | -63.56 | recover_long
data_downloaded | y |  data_downloaded
download_date_time | 2019-10-10 12:34:56 | download_date_time
filename | vr2w_12345_sample.vrl | filename
comments | Sample data | comments
