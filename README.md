#  JsonPowerDB 


[Documentation Link](http://login2explore.com/jpdb/docs.html)

## "Description."
### "This project is all about basics of JsonPowerDB (JPDB) and how to use JPDB for CRUD operations." 


### About JsonPowerDB:
- JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.


### Benefits of using JsonPowerDB
- Simplest way to retrieve data in a JSON format.
- Schema-free, Simple to use, Nimble and In-Memory database.
- It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
- It is low level (raw) form of data and is also human readable.
- It helps developers in faster coding, in-turn reduces development cost.




### Screenshots:

![Dashboard](https://github.com/BeAgarwal/JsonPowerDB/blob/master/Assets/Screenshots/Dashboard.PNG)

![Index Page](https://github.com/BeAgarwal/JsonPowerDB/blob/master/Assets/Screenshots/Index.PNG)

![Visualize](https://github.com/BeAgarwal/JsonPowerDB/blob/master/Assets/Screenshots/Server.PNG)

### "Release History"

0.3.2 / 2021-12-03
====================
* Added: New DBMS mode (pluggable) to upload, download and manage files and folders i.e. "PowerDrive" introduced.
* Added: ExecTime, ReqResTime, and ParseTime for all KvpDB APIs.
* Added: Methods for uploading, unloading, reloading & removing plugin apis in running JPDB instance.
* Added: ServerTime, execTime, parseTime, reqResTime with all JPDB responses.
* Added: Plugin API dashboard with upload, view, enable, disable and remove functionalities.
* Added: Plugin API tab in company dashboard to upload pluggable apii.
* Added: Serverless counter API, INIT command - alternative to incValue is now initValue.
* Added: documentation for Drive APIs.
* Improved: In IDL command, "ADD_INDEX" and "REMOVE_INDEX" command names are improved to "INDEX_COLUMN" and "UNINDEXED_COLUMN" respectively.
* Improved: API "send_email" validates email addresses for- to, cc, and bcc in JsonPowerDB.
* Improved: Error mail interval is reduced and can be set from the company dashboard.
* Improved: Type "REMOVE" for SET and SET_ALL cmd that will also check foreign Keys reference in other relations before removing from a given relation.
* Improved: First version of new jpdb-commons.js for version 0.0.5 created from 0.0.4
* Fixed: Various Important bugs fixed.

