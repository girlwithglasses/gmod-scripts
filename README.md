gmod-scripts

Collected scripts for GMOD tasks.


ipmapper.js

Extended from a geocoding script by Abhinay Rathore,
http://lab.abhinayrathore.com/ipmapper/


wiki.php

Scrapes the GMOD Users page on the wiki to create an array of users containing
URL, site name, and info. Queries a geo-ip server to get the location of the
website, and saves all this info as json for use by ipmapper.js.


sf-dl-stats.pl

gets the download stats of the gmod tools listed in @tool_list
creates a tab delimited table and a wiki formatted table
at present only gets stats for tools in the gmod sf project


mailing-list-stats.pl

gets the usage stats for various GMOD mailing lists, some on SF, some mailman.
creates a tab delim'd table and a wiki formatted table
