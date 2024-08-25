# Website-Ecom

You can Launch the website two way with LocalHost apcahe/tomcat and Docker.

Installation
Steps to Connect Manually (LocalHost Folder)

    1. Download the FinalProject.war.
    2. Download the data_export.sql.
    3. Import FinalProject.war into your Java IDE.
    4. Import data_export.sql into MySQL to create the schemas.
    5. Clean the project, build the project, and then run the code from your Java IDE.
    6. Make sure your SQL user name is root and the password is EECS4413, otherwise just change in the ConnectionProvider File
    7. Put http://localhost:8080/FinalProject/ in your browser and this will successfully launch the website.

Steps to Connect via Docker (Docker Folder)

    1. Ensure you have Docker Desktop installed.
    2. Download the data_export.sql.
    3. Import data_export.sql into MySQL to create the schemas.
    4. In your command line, run: docker pull dockerproject2194/web-service:1
    5. Then, in your command line, run: docker run -p 8080:8080 dockerproject2194/web-service:1
    6. Put http://localhost:8080/FinalProject/ in your browser and this will launch the website using Docker
