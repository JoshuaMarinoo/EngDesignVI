
# CPE 322
## Lab 7: ThingSpeak and Google Sheet
### Instructions:
![image](https://github.com/user-attachments/assets/778495ed-d10c-434d-8fe4-b2bc259e9261)


## Signing into Mathworks Thingspeak 
![image](https://github.com/user-attachments/assets/a03b705e-1a80-4ee9-a862-6ea7954f0ce4)
![image](https://github.com/user-attachments/assets/2662a542-f374-4bab-aec6-a479c5c1549f)

connected my matlab account to the thingspeak account and was able to sign in
---

## Creating new channel
![image](https://github.com/user-attachments/assets/5b1297a1-2cd6-4e25-b31f-a1dc6cfecfb7)
I created the channel cpu_loop with the fields cpu_pc and mem_avail_mb, and got the write API key so it could be used with code to write to the channel

---

## Running thingspeak_feed.py
![image](https://github.com/user-attachments/assets/8238c7ee-f922-4d6f-b7be-c7fe5c72e69d)
![image](https://github.com/user-attachments/assets/55c9c510-d47d-4672-887c-37090c90278e)

created a demo folder and copied thingspeak_feed.py and thingspeak_cpu_loop.py into it, then ran thingspeak_feed.py taking the API key and entering it in the terminal when prompted

--- 
## installing oauth2client and gspread
![image](https://github.com/user-attachments/assets/0218a589-e9f7-4c20-a2a9-c0c23941fca7)
installing the python packages needed for the next part

## creating and configuring the cpudata project in google cloud
![image](https://github.com/user-attachments/assets/fbcfb0ec-647d-4961-bbc0-85c180b624f7)
![image](https://github.com/user-attachments/assets/d01cad3f-adfe-4cfa-917b-14fb3c7bf565)
![image](https://github.com/user-attachments/assets/26ffd667-52a4-4141-a1eb-b5531b6994a3)
enabled the API's needed 


---
## Creating service account and getting JSON file
![image](https://github.com/user-attachments/assets/f8e9b16b-04b6-4efd-93b0-b0d396fe3003)
![image](https://github.com/user-attachments/assets/d8adfe5d-f4e4-457e-8c60-9e4fa1b8fb09)

created a service account with the JSON file associated with it so it can edit things


---

## Setting up spreadsheet
![image](https://github.com/user-attachments/assets/d6f4dcec-dc57-4a2a-a60a-0590dba5a720)
shared the sheet with service account and deleted rows and added headers


---

## Running code
![image](https://github.com/user-attachments/assets/55a1ac55-8333-4cbb-9156-8722de13e65c)
![image](https://github.com/user-attachments/assets/233b405f-c474-4c1d-bbca-d2edafa83996)

 I had to replace the name of the json file in the py code with the actual name I had, i did this through notepad I then ran it and saw the sheet get updated

---
## Summary
I learned how to use both google cloud and thingspeak platforms for API purposes, which seem very useful especially for IOT projects.

---
Author: Joshua Marino </br>
I pledge my honor that I have abided by the Stevens Honor System.



