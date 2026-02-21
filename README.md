This is code for the Java Spring Boot showcase site https://metrofinanceanalyst.azurewebsites.net/

It extracts data from azure postgres db to get the stock commentaries for the past 10 years from the Metrofinance Radio website
http://www.metroradio.com.hk/MetroFinance/ResearchTeam/ResearchReportsDetail.aspx

The commentaries are extracted via a node.js etl script periodically into the db

User can search the commentaries either by stock code or by the recommending institution name

The source data is not well cleansed. I have partially cleansed the data Hence there are some similar entries in both stock name and institution name

<img width="628" height="548" alt="image" src="https://github.com/user-attachments/assets/54c05747-86dd-4545-a555-1ff7d9c3e95e"/>
<img width="545" height="154" alt="metrof_1" src="https://github.com/user-attachments/assets/d3b3245f-29a6-4199-a38c-4a45350d9616" />

<img width="1387" height="575" alt="metrof_3" src="https://github.com/user-attachments/assets/0f2fa285-9f02-402b-bdcd-2619f51fd16d" />
<img width="1483" height="752" alt="metrof_2" src="https://github.com/user-attachments/assets/b55e9aae-3780-45d0-8309-def188c64307" />
