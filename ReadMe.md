# Clinical Final Project
----------
## Team: 18
## Submitted By:  
Alzahraa Eid Abd El-Fattah

Alzahraa Mahmoud

Amany Bahaa El-Din Mustafa

Esraa Sayed Mustafa

Mustafa Tawfik

-------------
------------



## Pre-Requistics:
1) Create data base with name ***clinicaldatabase***.
2) In data base import file ***clinicaldatabase.sql***.
3) Run file ***server.py***

---------------
# Server Flow
1) Home page:
![Alt Text](images/screen1.png)
----
2) When we choose **Radiology** :
![Alt Text](images/screen2.png)
the department's page appear with:

    1. The department's devices with their serial numbers

    2. Three buttons|:

        1. When we click on **View Devices' Details** , department's devices' details are reviewed
![Alt Text](images/screen3.png)

        2. When we click on **Daily Inspection reporting**, we can add a new daily inspection report for all department's devices
   ![Alt Text](images/screen4.png)
   first, you need to insert date of the day
   then, check each point for each device and write your comment
   ![Alt Text](images/screen5.png)
   after finishing inspection report for all devices, you need to add a signature and click submit to save the results at the data base
        3. When we click on **View Department's Daily inspection Report**, a review report for all devices in the department appears
   ![Alt Text](images/screen6.png)
   ![Alt Text](images/screen7.png)
   ![Alt Text](images/screen8.png)
   ![Alt Text](images/screen9.png)
   ![Alt Text](images/screen10.png)
   while , if you need a report for one device only, you need to enter its serial number in the input box, 
   ![Alt Text](images/screen11.png)
   for an example, if you need to get the report for **Mammography** device , you have to enter its serial number 
   ![Alt Text](images/screen13.png)
   to get its report
   ![Alt Text](images/screen12.png)
   #### Comments:
   We have faced problems during searching for daily inspection for specific devices (Dye Injector , Diagnostic X-Ray , FCR),
   so we couldn't do a report for them, and an error page appears if their serial number is entered.
   for an example, if FCR serial number is entered, this page appears:

   ![Alt Text](images/error.png)





------------------

3) When we choose **Open Heart**:
![Alt Text](images/open1.png)
the department's page appear with:

    1. The department's devices with their serial numbers

    2. The input box for PPM reporting, for applying report for each device by entering its serial number
    ![Alt Text](images/open3.png)
    for an example, if we need to apply report for **Exercise Cardiac Report** 
    ![Alt Text](images/reportPPM.png)
    after filling the report , you need to click submit to save the results at the data base.


    3. The input box for reviewing each device's PPM report by entering its serial number

          ![Alt Text](images/open4.png)

       for an example , if we search for Exercise ECG device's report
       ![Alt Text](images/open6.png)



    4. Two buttons|:

        1. When we click on **View Devices' Details** , department's devices' details are reviewed
![Alt Text](images/open2.png)

        2. When we click on **View Department's PPM Report**, we can add a new daily inspection report for all department's devices
   ![Alt Text](images/report1.png)
   ![Alt Text](images/report2.png)
   ![Alt Text](images/report3.png)
   ![Alt Text](images/report4.png)
   ![Alt Text](images/report5.png)


------------------------------

2) When we choose **Catheter** :
![Alt Text](images/catheter.png)
the department's page appear with:

    1. The department's devices with their serial numbers

    2. Three buttons:

        1. When we click on **View Devices' Details** , department's devices' details are reviewed
![Alt Text](images/catheter1.png)

        2. When we click on **Daily Inspection reporting**, we can add a new daily inspection report for all department's devices
   ![Alt Text](images/cath1.png)
   first, you need to insert date of the day
   then, check each point for each device and write your comment
   ![Alt Text](images/cath2.png)
   after finishing inspection report for all devices, you need to add a signature and click submit to save the results at the data base
        3. When we click on **View Department's Daily inspection Report**, a review report for all devices in the department appears
   ![Alt Text](images/cath3.png)
   ![Alt Text](images/cath4.png)
   ![Alt Text](images/cath5.png)
   ![Alt Text](images/cath6.png)
   ![Alt Text](images/cath7.png)
    while , if you need a report for one device only, you need to enter its serial number in the input box, 
   ![Alt Text](images/screen11.png)
   for an example, if you need to get the report for **Suction Machine** device , you have to enter its serial number 
   ![Alt Text](images/cath8.png)
   to get its report
   ![Alt Text](images/cath9.png)


#### Comments:
  We needed to install:
  - Flask via "pip install flask"
  - "pip install anaconda mysql-connector-python"
  

--------------------