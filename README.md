# Metascope

Metascope is a metadata management tool built at Otto Group. Metascope is able to collect technical, operational and business metadata from your Hadoop Datahub and display the metadata to the user through a web service.
Metascope serves as an extension to [Schedoscope](https://github.com/ottogroup/schedoscope). 

Check out the [**wiki**](https://github.com/kaaas/metascope/wiki) to learn more about Metascope.

## Features

* Overview of data: Get a complete overview of all your tables and partitions and their metadata
* Search your data: All metadata is indexed and is ready for query
* Apply filters: Metascope will let you apply filter and facets to your query to find the datasets you need in seconds
* Data Lineage: Get dependency and lineage information on table and partition level
* 

## Getting started

### Manual Build:
1. Clone this repo: `git clone https://github.com/kaaas/metascope`.

2. Build with maven: `maven install`.

3. The .../target/metascope folder includes all necessary files to execute Metascope.

### Quick Start:
Check out [Quick Start Guide](https://github.com/kaaas/metascope/wiki/Quick-Start-Guide)

## Origins
The project was conceived at the Business Intelligence department of Otto Group.

## License
Licensed under the [Apache License 2.0](https://github.com/kaaas/metascope/blob/master/LICENSE)
