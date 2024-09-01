Steps to Connect via Docker (NewDocker Folder)
    
    1. Ensure you have Docker Desktop installed and log in your account.
    2. Download the data_export.sql.
    3. Import data_export.sql into MySQL to create the schemas.
    4. In your command line, run: docker pull dockerproject2194/web-service:1
    5. Then, in your command line, run: docker run -p 8080:8080 dockerproject2194/web-service:1
    6. Put http://localhost:8080/FinalProject/ in your browser and this will launch the website using Docker

Note: it does not matter where you enter the commands. You can be in any directory.

To Log in with administration

    1. Email is EECS4413@gmail.com 
    2. Password is 4413
