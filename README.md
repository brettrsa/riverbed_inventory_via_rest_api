# riverbed_inventory_via_rest_api

This script grabs Riverbed inventory info such as linetag/hostname, model, serial number and software version.
The data is then piped to an awk script with the output that looks like the below,


======================================================
HOST                MODEL      SERIAL #       VERSION
======================================================
abc-abc-abc-rb1      CX570      EC6GSXXXXXX   8.6.1
