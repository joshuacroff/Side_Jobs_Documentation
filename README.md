# Side_Jobs_Documentation
This repository contains documentation for projects that I've taken on because I thought they were interesting or I was looking to gain new skills and experience.

## Relocation Impact on Employee Commutes
**Overview & Project Background**

I took on this project because I've recently become really interested in understanding what impact relocating an office has on employee commutes. My former employer relocated 150 or so of us from an office which was quiet convenient for me and many others to a location that was far from transit oriented and added about 20 - 30 minutes one-way to my commute! As a GIS Analyst, I thought up an idea to measure the impact of an office relocation on employees but haven't had a reason to apply it up until the last week.

A friend of mine is putting together some information to present to their employer which could potentially influence where they decide to relocate their office - a decision that will impact **_~170 + employees_**. Employers considering an office relocation in the Bay Area face unique challenges as office space is often hard to come by and the cost per square foot varies greatly depending on location.

In Q1 of 2017, the [**Annual cost to rent 20,000 square feet of office space in the Bay Area**](http://image-store.slidesharecdn.com/bb2f8eef-f098-402f-8611-205224c4cfd8-original.png) was at a high of **_$116.28/SF/YR_** in **Palo Alto** and a low of **_$25.29/SF/YR_** in **Walnut Creek**.

Besides price, employers are likely taking a number of factors into account when considering relocation such as **lease terms, layout, amenities (amenities offered on-site or amenities within a short distance of the office space), parking or adjacency to transit**. Often, impact on existing or future employees is factored in  but attempting to weigh the concerns of a large team can be tenuous. In a region like the Bay Area, you may risk loosing valuable employees depending on where you locate.

Faced with difficult multi-criteria choices like those outlined above, it's useful to leverage tools which can provide insights and ultimately inform where you choose to locate your office.

**Methodology**

***Summary***

For this analysis, three static [isochronal maps](http://wiki.openstreetmap.org/wiki/Isochrone) were created based on three proposed office locations. The three maps show [commute times](https://en.wikipedia.org/wiki/Isochrone_map#/media/File:Drive_time_isochrones_airports_northern_Finland.png) instead of commute distance from each proposed location.

Other examples include [OneBayArea / Maps](http://maps.onebayarea.org/travel_housing/#origin=375+Beale+St,+SF,+CA&mode=da&time=AM&scenario=2010&xyz=9.00/37.7880/-122.3915), which is an interactive tool that allows users to see what areas are accessible within a given time frame. Users can choose a number of filters including:
- travel times
- travel mode
- time of day
- median home prices
- and simulation year
Tool uses [Metropolitan Transportation Commission -511 Real-Time Travel Information](http://511.org/)

Commute times were measured in 15 - minute increments radiating outward from the proposed office location. Areas accessible within pre-defined increments of time were symbolized with different colors to indicate places accessible from proposed office locations in a single-occupant auto during AM Commute Time **(8:00 A.M. - 11:00 A.M.)**.

Employee home addresses were [geocoded](https://en.wikipedia.org/wiki/Geocoding) and added to the map to show the commute times of each employee form each of the proposed office locations. Additionally, reports were generated to provide employees with address - level commute information as well as aggregated average employee commute data for each proposed location.

***Analysis Tools***

***Detailed Methodology***






