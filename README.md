# :oncoming_taxi: Taxi Service :oncoming_taxi:
It is a great service for a taxi company  .
Here you can manage your cars , drivers and manufacturers just in 2 clicks.
## :bulb: Functionality :bulb:
>- _:lock: Driver **registration** and **authentication** :lock:_.
>- _:key: Possibility to **login / logout** :key:_
>- _:blue_car: Cars management: **add new car | delete car | add driver to car | display all cars :blue_car:**_
>- _🧔‍ Drivers management: **register new driver | delete driver | add or remove driver from car | display all drivers 🧔‍**_
>- _:factory: Manufacturers management: **add new manufacturer | remove manufacturer | display all manufacturers :factory:**_
>- _:eyes: Possibility for driver **to see his/her current cars** :eyes:_
## :file_folder: Structure :file_folder:
>_This project has **N-tier architecture**. It consists of:_
>>**Controller** - accept http requests from users and display information.
>
>>**Service** - all business-logic is located here.
>
>>**DAO** - all interaction with DataBase is located here
## :gear: Technologies :gear:
>:pushpin: _**Java 11**_
>
>:pushpin: _**Maven**_
>
>:pushpin: _**MySQL**_
>
>:pushpin: _**JDBC**_
>
>:pushpin: _**Tomcat (9.0.50)**_
>
>:pushpin: _**JSP**_
## :man_shrugging: How can I use it ? :woman_shrugging:
>- _Step 1_ - **Fork this repository**
>- _Step 2_ - **Open IntelliJ IDEA and write `git clone <SSH link>` in console**
>- _Step 3_ - **Configure ConnectionUtil class**
>```java
>private static final String URL = "URL;
>private static final String USERNAME = "USERNAME";
>private static final String PASSWORD = "PASSWORD";
>private static final String JDBC_DRIVER = "JDBC_DRIVER";
>```
>- _Step 4_ - **Run script in your DBMS (MySQL for instance) from "init_db.sql" file in "resources"
   package in order to create needed tables**
>- _Step 5_ - **Install Tomcat. (you can install it [here](https://tomcat.apache.org/download-90.cgi)) .**
>- _Step 6_ - **Add Tomcat server in configurations**
>- _Final Step_ - **Run project and enjoy using it ! :wink:**
___
