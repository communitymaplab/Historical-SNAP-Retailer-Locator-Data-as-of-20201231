1.	Downloaded “Historical SNAP Retailer Locator Data as of 20201231.csv” from USDA, the file has 924476 rows, 589739 rows have location information, duplicated stores are included in this data.
2.	Rows without location information are fuzzy matched with “snap_retailers_usda_2005-2020.csv”， 30215 rows are matched.
3.	Remaining unmatched rows are geocoded through ArcGIS PRO, 239721 are geocoded.
4.	Remaining unmatched rows are geocoded through Google.
