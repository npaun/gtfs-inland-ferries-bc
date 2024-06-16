# Unofficial GTFS feed for BC's inland ferry system

This is an unofficial GTFS feed for the BC's inland ferry system. 

For more information on the service please see the [official website](https://www2.gov.bc.ca/gov/content/transportation/passenger-travel/water-travel/inland-ferries).

### Permalink to download the latest feed: <https://github.com/npaun/gtfs-inland-ferries-bc/blob/master/inland-ferries-bc-gtfs.zip>

## Scheduled services

* Most service operates every day of the year (service\_id R).
* Upper Arrow Lake Ferry
    - Vessel: MV Columbia
* Needles Cable Ferry
    - Vessel: CF Needles
    - Scheduled service only from 05:00 to 22:00. On-demand service is available during the night.
* Kootenay Lake Ferry 
    - Vessel: MV Osprey 2000
    - Additional sailings June to September using the MV Balfour (service\_id KOOTLK\_SUMMER).
    - If the highway over Kootenay Pass is closed, service will operate 24 hours a day.
* Francois Lake Ferry 
    - Vesssel: MV Francois Forester
    - Some school sailings do not operate in July and August (service\_id FRANCOIS\_SCHOOL).


## On-demand service

The remaining service operates 'on-demand'. These trips are not currently included in the feed but will be added later, using the [GTFS-Flex](https://gtfs.org/extensions/flex/) extension.

* Adams Lake Cable Ferry
   - Vessel: CF Adams Lake II
* Arrow Park Cable Ferry
   - Vessel: CF Arrow Park III
* Barnston Island Ferry
    - MV Centurion VI (tug) and Barnston Island No. 3 (barge)
* Big Bar Reaction Ferry
    - When water is low or icy, an aerial tramway operates for passengers only.
* Glade Cable Ferry
   - Vessel: CF Glade II
* Harrop Cable Ferry
   - Vessel: CF Harrop II
* Little Fort Reaction Ferry
* Lytton Reaction Ferry
* McLure Reaction Ferry
* Needles Cable Ferry (between 22:00 and 05:00)
   - Vessel: CF Needles
* Usk Reaction Ferry
   - When water is low or icy, an aerial tramway operates for passengers only.

## About GTFS

[GTFS](https://gtfs.org) is the industry standard for publishing public transit schedules. It's used for metro and bus systems throughout the world, but any scheduled or on-demand service can be represented in this format. This GTFS feed allows for the inland ferries to appear in trip planning apps like [Transit](https://transit.app) and many others. When ferry service connects with bus service, trips can be planned using both modes.

## Disclaimer

The data is not produced, approved or otherwise associated with the BC Ministry of Transportation and Infrastructure. The data is provided to you on 'as is' and 'as available' basis, without any express or implied warranty of any kind, including without limitation, the implied warranties of merchantability, fitness for a particular purpose, accuracy and non-infringement. 
