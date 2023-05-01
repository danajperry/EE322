## Lab 7: ThingSpeak and Google Sheets

First, I signed up and logged into MathWorks ThingSpeak.
![Installations](ipinstallpsutillab7.png)

Then, I ran thingspeak_cpu_loop.py or thinkspeak_feed.py in a demo folder and installed gspread and oauth2client.
![Cat cpu](catcpulooplab7)
![Cat feed(catfeedlab7.png)

Then I logged in the Google Cloud Platform Identity and Access Management, created a project cpudata, enabled both Drive API and Sheets API, created and downloaded service account JSON key file
![API key](API key.png)

Next, I started a new Google sheet cpudata, shared it with the client email in the JSON file, deleted Rows 2 to 1000, and edited the header cells
1[JSON](jsonfilelab7.png)

Finally, I ran cpu_spreadsheet.py with the JSON key file in a demo folder and got the following results:

![Chart 1](part1lab7.png)

![Part 2 Chart](lab7pt2.png)
![Part 2 Chart2](lb7part2.1.png)
![Fig 1](lab8fig1.png)




