The following layers exist in the OTN geoserver:
1. etn_projects
    - jb
2. etn_stations
    - collectioncode: project code
	  - seriescode: series code
	  - ocean: ocean where station is located
	  - station_name: name of station
	  - station_type: type of station
	  - stn_lat: latitude of station
	  - stn_long: longitude of station
	  - stationstatus: status of station
	  - locality: locality of station
	  - model: model of station
	  - instrumenttype: type of instrument
	  - deploy_date: first date of station
	  - last_download: date station was last downloaded
	  - last_recovery_date: last date station was recovered from
	  - is_active_now: if station is active
	  - downloads: number of downloads
	  - off_set: offset
	  - the_geom: geometric representation of location
	  - depth_m: depth of station
3. etn_animals
    - type: type of transmitter
    - animal_id: identifier of animal
    - project: project code
    - model: model of transmitter
    - serial_number: serial number of transmitter
    - id_code: id code of tag
    - tag_code_space: code space of tag
    - implant_type: implant type
    - implant_method: implant method
    - activation_date: activation date
    - est_tag_life: estimated tag life
    - tagger: tagger
    - owner_pi: principal investigator of the owner of tag
    - owner_organization: organization of the owner of tag
    - common_name: common name of animal
    - scientificname: scientific name of animal
    - capture_location: location where animal was captured
    - capture_latitude: latitude where animal was captured
    - capture_longitude: longitude where animal was captured
    - wild_or_hatchery: wild indicator of animal
    - stock: stock of animal
    - length: length of animal
    - weight: weight of animal
    - length_type: length type of animal (e.g. total, standard)
    - length2: 2nd length measurement of animal
    - length2_type: length2 type of animal (e.g. total, standard)
    - life_stage: life stage of animal
    - age: age of animal
    - age_units: age units of animal (e.g. months, years)
    - sex: sex of animal
    - dna_sample: dna sample
    - treatment_type: type of treatment
    - release_location: location where animal was released
    - release_latitude: latitude where animal was released
    - release_longitude: longitude where animal was released
    - utc_release_date_time: time when animal was released in UTC
    - recapture_date: date when animal was recaptured
    - capture_depth: depth where animal was captured
    - temperature_change:temperature change
    - holding_temperature: holding temperature
    - preop_holding_period: holding period of animal pre-operation
    - post_op_holding_period: holding period of animal post-operation
    - surgery_location: location where animal had surgery
    - date_of_surgery: date when animal had surgery
    - surgery_latitude: latitude where animal had surgery
    - surgery_longitude: longitude where animal had surgery
    - sedative: sedative
    - sedative_concentration: concentration of sedative
    - anaesthetic: anaesthetic
    - buffer: buffer
    - anaesthetic_concentration: anaesthetic concentration
    - buffer_concentration_in_anaesthetic; buffer concentration in anaesthetic
    - anesthetic_concentration_in_recirculation: anesthetic concentration in recirculation
    - buffer_concentration_in_recirculation: buffer concentration in recirculation
    - dissolved_oxygen: dissolved oxygen
    - comments: notes about animal
    - catalognumber: unique identifier of animal
4. etn_deployments
    - receiver: receiver
    - transmitter: transmitter
    - model: receiver model
    - receiver_status: receiver status
    - ar_model_number: AR model number
    - ar_serial_number: AR serial number
    - projectname: longname of project
    - projectcode: project code
    - projectmember: project member
    - drop_dead_date: date receiver was dropped
    - download_date: download date
    - deploy_date: date receiver was deployed
    - recover_date: date receiver was recovered
    - bottom_depth: bottom depth of receiver
    - riser_length: riser length of receiver
    - instrument_depth: depth of instrument
    - check_complete_time: time check was complete
    - sync_date_time: date of sync
    - voltage_at_deploy: voltage at deployment
    - ar_confirm: AR was confirmed
    - filename: file name
    - data_downloaded: data was downloaded
    - recovered: receiver was recovered
    - voltage_at_download: voltage at download
    - time_drift: time drift
    - comments: notes about receiver
    - catalognumber: unique identifier for receiver
5. etn_detections
    - project: project code
    - datetime: datetime of detection
    - receiver: receiver of detection
    - transmitter: transmitter of detection
    - transmitter_name: transmitter name of detection
    - transmitter_serial: transmitter serial of detection
    - sensor_value: sensor value of detection
    - sensor_unit: sensor unit of detection
    - station_name: station name of detection
    - latitude: latitude of detection
    - longitude: longitude of detection
    - receiver_catalognumber: link to unique identifier of receiver deployment in etn_deployments
    - tag_catalognumber: link to unique identifier of animal in etn_animals, or None if it could not be matched