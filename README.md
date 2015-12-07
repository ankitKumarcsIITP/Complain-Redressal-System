# Complain-Redressal-System

This is a web application based on Django framework used to implement a web centric Complaint Redressal System. This application uses MySQL database.

Instructions :

    Python version 2.7.6
    django 1.7
    Create a database (name as given in /crs/crs/settings.py) file.
    Change /crs/crs/settings.py->DATABASES according to mysql connection details
    download link of MySQL-Python connector : http://cdn.mysql.com/Downloads/Connector-Python/mysql-connector-python_2.0.3-1debian7.6_all.deb
    for all tables in manage.py comment managed = False if you want to create them using django
    for using encryption run folowing commands :
        - sudo apt-get install libffi-dev
        - sudo pip install bcrypt

    for generating dynamic pdf by django install report lab :
    sudo pip install reportlab

    For viewing ER diagram of MySQL database :
        Using MySQL workbench

            Install MySQL workbench (sudo apt-get install mysql-workbench)

            Either create the ER diagram yourself or see file /crs/login/ER.mwb

        Directly view pdf or image
            You can access .pdf file in /crs/login/ER.pdf

            You can access .png file in /crs/login/ER.png 
