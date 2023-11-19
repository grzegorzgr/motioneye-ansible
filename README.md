Simple ansible directory for installing dependencies required to run MotionEye on Raspbian 11+

Contains 3 playbooks:
1) Bootstrap - used to install dependencies and setting up RPI Camera v2
2) Motioneye - installs python dependencies as well as starts the motioneye webserver
3) Nginx - Used to ensure SSL and proxypass for both MotionEye UI and Live feed
