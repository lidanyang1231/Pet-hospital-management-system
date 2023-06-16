Environment configuration: JDK 1.8, mysql 5.7 or mysql8, maven, eclipse or idea
Main technologies: SpringBoot, MyBatis, jsp, mysql

After decompressing the files in the compressed package, do the following:
1. Create a new database and set the name to: phms. Import the 'phms.sql' file under the 'sql' folder into the 'phms' database.
Character Set: utf8mb4
Collation: utf8mb4_bin

2. Open the 'phms' folder in idea or eclipse.

3. In 'application.properties', change the database user name and password to the correct information of the current computer.

4. Change the bytecode version of the project to 'jdk8' or 'jdk1.8'. Then change the language version to 8 in the project structure module.

5. In the pom.xml file, change the mysql version to the mysql version of the current computer, and version 5.7 is the best.

6. Update dependencies.

7. Set spring boot to jdk8 as well.

Then you can run the project normally.

Open the URL after the project is running: localhost:8186