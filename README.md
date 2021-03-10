# PHP CRASH COURSE
```AMP = Apache + MySQL + PHP```

### Operating Systems
- **Linux**: LAMP
- **Windows**: WAMP

### Web applications are built with multiple tiers.
- **Client**: Web browser
- **Web**: HTTP server (Apache)
- **Business**: Application server (PHP)
- **Data**: Database server (MySQL)

### Standard Ports
- **HTTP**: Port 80
- **MySQL**: 3306

### WAMP SERVER Homepage
- http://localhost/

### PHP MyAdmin
- http://localhost/phpmyadmin/

### Troubleshooting
- **Check ports**: netstat -a -o | find "LISTENING"

### How to get started for Windows
- Go to this url (https://sourceforge.net/projects/wampserver/) and download WAMP.
- When asked:
    - [X] MariaDB
    - [X] MySQL
- After installation is complete, right click on your taskbar and go to taskbar configuration.
- Deactivate second function.
- To start working, open WAMP.
- In the taskbar an icon of WAMP will pop up, there you can manage WAMP.
- Click it and open localhost (located up-top when click the icon): http://localhost/
- That's the main page to manage WAMP!
- To open the database go to: http://localhost/phpmyadmin/
- You've completed the first steps to run WAMP! Congratulation! :D

### Add an Alias
- Click in the WAMP icon.
- Go to Apache=> Alias directories=> Add an alias.
- Inside add the following when asked:
    - [X] Name of the domain of your choice.
    - [X] The path of your folder. NOTE: Change the '\' with '/' and add '/' to the end.
        Recommended path: *wamp64/apps/<your_folder>/*
- Example:
    1. test
    2. C:/wamp64/apps/test/
- Once this is done access your project like this: http://localhost/test/

