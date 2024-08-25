# Website-Ecom

You can Launch the website two way with LocalHost apcahe/tomcat and Docker.

Installation
Steps to conenct manually (LocalHost Folder)
                  1. download the FinalProject.war
                  2. Download the data_export.sql
                  3. Import FinalProject.war in JAVA IDE
                  4. Import data_export.sql in MySQL to create the schemas
                  5. Clean the project and built project and then Run the code from Java IDE and you will successfully launch the code

                  
Steps to connect Docker
                    1. Have Docker Desktop
                    2. Download the data_export.sql
                    3. Import data_export.sql in MySQL to create the schemas
                    4. in your command line do docker pull dockerproject2194/web-service:1
                    5. then again in your command line do docker run -p 8080:8080 dockerproject2194/web-service:1


Steps to Connect Manually (LocalHost Folder)

    1. Download the FinalProject.war.
    2. Download the data_export.sql.
    3. Import FinalProject.war into your Java IDE.
    4. Import data_export.sql into MySQL to create the schemas.
    5. Clean the project, build the project, and then run the code from your Java IDE.
    6. This will successfully launch the website.

Steps to Connect via Docker

    1. Ensure you have Docker Desktop installed.
    2. Download the data_export.sql.
    3. Import data_export.sql into MySQL to create the schemas.
    4. In your command line, run: docker pull dockerproject2194/web-service:1
    5. Then, in your command line, run: docker run -p 8080:8080 dockerproject2194/web-service:1
    6. This will launch the website using Docker.
