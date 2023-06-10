# Console-Based-App-Spring-Framework-
This is a layered approach project in spring framework.
This project is all about calcutating percentage of marks obtained.
In this we have Controller, Service and DAO layer(JDBC).
Step1 - Using Controller layer here i am taking input data from user in String form and keeping it in VO(value object). Values are Student name, address, marks obtained in subjects and the maximum marks.
Step2 - In Service layer value object will be converted into DTO i.e. Data Transfer Object and in DTO variables are of its respective types. Like marks and percentage will be chaged to float type. Also calcutation of percentage will be done in service layer only.
Step3 - Now DTO will be converted into BO(Business Object) and the calculated value of percentage will be injected which will interact with persistance logic for database management.
Step4 - For dataSource we are using HikariCp which is third party framework, as Spring supports the integration HikariCp.




