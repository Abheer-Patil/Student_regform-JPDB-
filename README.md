# Student_regform-JPDB-

Project Title : Student Registration Form

Description : The frontend is created using HTML5 ,bootstrap and ajax is used to map the objects , collect the details 
from the form and to establish connection to the JSONPowerDB using token , api and endpoint URL.
The application takes the information of the student and stores it in the Database .

It also has a CRUD operation project done in JSONpowerDB with all methods such as PUT, PUT_ALL, REMOVE, UPDATE.


Benefits of using JsonPowerDB:

- Simplest way to retrieve data in a JSON format.
- Schema-free, Simple to use, Nimble and In-Memory database.
- It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
- It is low level (raw) form of data and is also human readable.
- It helps developers in faster coding, in-turn reduces development cost.


RELEASE NOTE:
0.3.2 / 2021-12-03
==================

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


Example Of USE:
![image](https://user-images.githubusercontent.com/113827619/195524705-939ab36d-99e8-4d88-8fc5-c28b8e52115f.png)

![image](https://user-images.githubusercontent.com/113827619/195524924-65f0a02f-ddb7-4e6f-92f0-803063cfa86d.png)

![image](https://user-images.githubusercontent.com/113827619/195525487-95bcf7eb-3b56-41e7-bad3-385e00516afb.png)




