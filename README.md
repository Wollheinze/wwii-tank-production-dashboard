# WWII Tank Production Dashboard

![Dashboard Overview](dashboard_overview.png)

## Overview

I built this Power BI dashboard to compare selected World War II tank production records by country, model, class, year, and production period.

I kept the scope limited to light, medium, and heavy tanks so the dataset would remain consistent and manageable.

## Dashboard Features

* Total recorded production units
* Leading country by recorded production
* Most-produced tank class
* Peak production year
* Production comparison by country and year
* Light, medium, and heavy tank comparison
* Country, model, and production-period filters

## What I Did

* Collected and organized the data in Excel
* Structured the records by country, model, class, year, and period
* Imported the dataset into Power BI
* Created DAX measures for the main indicators
* Built interactive charts and filters
* Assigned Pre-War records to 1938 as a reporting convention

The Peak War Year measure returns a blank value when only Pre-War records are selected because those records do not represent a single production year.

## Key Findings

* In this dataset, the USSR has the highest recorded production quantity.
* Medium tanks are the most-produced class.
* 1943 is the peak wartime production year.
* Recorded production increased significantly between 1941 and 1943.

## Scope and Limitations

This dataset includes selected light, medium, and heavy tank models. It is not a complete record of every armored fighting vehicle produced during World War II.

The 1938 category contains aggregated Pre-War records and does not mean that every unit was produced in that exact year.

The French figures mainly represent deliveries rather than strictly factory-completed production.

I excluded self-propelled guns and tank destroyers to keep the project focused on tank classes.

## Tools

* Microsoft Power BI Desktop
* Microsoft Excel
* DAX

## Files

* [`ww2_tank_production_dashboard.pbix`](ww2_tank_production_dashboard.pbix) — Power BI report
* [`ww2_tank_production_data.xlsx`](ww2_tank_production_data.xlsx) — source dataset
* [`dashboard_overview.png`](dashboard_overview.png) — dashboard preview

## How to View

Download the `.pbix` file and open it with Microsoft Power BI Desktop.

## Data Sources

* [German armored fighting vehicle production during World War II](https://en.wikipedia.org/wiki/German_armored_fighting_vehicle_production_during_World_War_II)
* [French combat vehicle production during World War II](https://en.wikipedia.org/wiki/French_combat_vehicle_production_during_World_War_II)
* [Soviet combat vehicle production during World War II](https://en.wikipedia.org/wiki/Soviet_combat_vehicle_production_during_World_War_II)
* [American armored fighting vehicle production during World War II](https://en.wikipedia.org/wiki/American_armored_fighting_vehicle_production_during_World_War_II)
* [Type 97 Chi-Ha](https://en.wikipedia.org/wiki/Type_97_Chi-Ha_medium_tank)
* [Type 98 Ke-Ni](https://en.wikipedia.org/wiki/Type_98_Ke-Ni_light_tank)
