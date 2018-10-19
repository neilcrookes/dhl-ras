# dhl-ras

DHL Remote Areas List

The JSON file is created from the DHL Remote Area List

Current version is from the June 2018 PDF http://www.dhl.com/content/dam/downloads/g0/express/services/surcharges/dhl_express_remote_areas.pdf

## Objectives

1. Preserve leading zeros
1. Expand ranges, so `0010 - 0012` actually yields 3 items: `0010`, `0011` and `0012`
1. Key by ISO 3166-1 alpha-2 code
1. Fix errors in the PDF published by DHL (e.g. Missing "NORWAY") 
