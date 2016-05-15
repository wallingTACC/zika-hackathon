# Zika Hackathon
Data Science Hackathon with UT Austin | Mosquito Transmitted Viruses

This repository has been created in support of a Cloudera Cares Hackathon on May 16th 2016 in Austin, TX
http://www.meetup.com/Cloudera-Cares/events/229135008/

The hackathon will focus on reducing mosquito borne virus infections by analyzing data on mapping mosquito travel, climate, bodies of water and historical virus analysis.

# Additional Datasets
Zika Data Repository - https://github.com/cdcepi/zika - CDC data and scripts

BuzzFeed News - https://github.com/BuzzFeedNews/zika-data - CDC, ECDC and other parsers

Zika data to CDC format - https://github.com/ndssl/zika_data_to_cdc - data to CDC format

D3.js map of the Zika virus outbreak - https://github.com/alexandercbooth/zika - ECDC zika notebook

Matt Holbrook https://github.com/holbrojm/zika - Sample jupyter notebooks with Zika

Shaun Carland - https://github.com/shauncarland/zikavirus - PAHO scrapper in Ruby

Mosquito Occurrence Dataset - http://www.gbif.org/dataset/88e38292-f762-11e1-a439-00145eb45e9a - Walter Reed Biosystematics Unit, Smithsonian Institution

## How to contribute
Follow the [how to contribute](CONTRIBUTE.md) guide to contribute to the Zika Hackathon repo from your fork or local git clone.

## License
Any new content, data or information that is not subject to a prior license is provided under the Apache Software License 2.0. See the file [LICENSE](LICENSE) for more information.

# Compute Resources

We have created an allocation on TACC's Wrangler data system(https://www.tacc.utexas.edu/systems/wrangler).  Wrangler includes 500TB of high speed flash storage attached to 96 24-core, 128GB RAM compute nodes.  Optimized versions of popular data anatlytic tools are pre-installed, including R, Python and Hadoop.

Please see David Walling in conf1 for getting access to this system.

## Pre-staged Datasets

We have pre-staged datasets related to this hackathon at the following location:  /data/shared/zika

In addition to the data available in github, we have included a collection of aerial photography images of the Austin area, as well as a download of the open access subset from PubMed.

## Resource Reservations

For this hackathon, we have created a 10 node Hadoop cluster available under the reservation id: hadoop+Zika+1487

In order to submit jobs to this cluster, you must:

* create a TACC account.
* see David Walling to get added to the project allocation.
* ssh to wrangler: $> ssh username@wrangler.tacc.utexas.edu
* create an interactive session: $> idev -r hadoop+Zika+1487
* interact with the cluster from the commandline: Ex. hadoop fs -ls /tmp/zika

## Interactive Consoles

Rstudio, Jupyter and general VNC sessions are avaiable to the Wrangler compute nodes from our visualization portal:  http://vis.tacc.utexas.edu

After logging into the portal, select the Wrangler tab and follow the prompts for launching your sessions.


