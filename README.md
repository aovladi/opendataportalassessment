# opendataportalassessment
Assessment of russian open data portal

Steps to run program
1.	 Register on data.gov.ru and get your own API key
2.	 Install mysql database
3.	 Create database 
4.	 Run sql scripts dataset.sql , organization.sql, topics.sql
5.	 Install NetBeans
6.	 Put downloaded folder EN into NetBeansProjects (usually it is in C:\Users\<your user_name>\Documents\NetBeansProjects)
7.	 Open EN project in NetBeans
8.	 in main package open Work.java and interfacee.java

Work.java
1.	insert your api key in line 44 (public static String APIkey = "?access_token=...";)
2.	in start_conn() insert all parametrs for your database

interfacee.java
1.	lines 47-49: insert parametrs to connect your database 
variable connection should look like "jdbc:mysql://localhost:3306/<database name>"
