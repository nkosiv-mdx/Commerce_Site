# Create E-Commerce Site

- Practice any automation
- Access to Database and API
- Full functional site
- Perform/Practice
  - API Testing
  - Frontend (UI) Testing
  - Load Testing

__________________________________________________________________
- Using WordPress + Plugin
- Customizable
- Different options on how to run WordPress
- Usefull knowledge to create real site to sell items
__________________________________________________________________

# Options to run WordPress
1) AMPPS - https://ampps.com/
   - Pro
       - Easy to use
       - Many functionalities
       - Fewer steps to setup
   - Con
       - Not working on Latest Mac OS
       - May be not developed anymore
2) Docker - https://docker.com/
   - Pro
       - Very stable
       - Fewer steps to setup
   - Con
       - Docker knowledge
3) LOCAL - https://localwp.com/
   - Pro
       - Easy to use
       - Specifically for WordPress
   - Con
       - Behave differently for Windows and Mac
       - Extra step to connect to db with port
       - Extra step to access from a Docker
4) MAMP - https://mamp.info/
   - Pro
       - Easy to use
       - Stable
   - Con
       - None
__________________________________________________________________
# Running WordPress with MAMP
1) Download MAMP & MAMP PRO -> https://www.mamp.info/en/downloads/
2) Install MAMP with all default settings.
3) Save "Document Root" folder path -> on the References from the top menu
4) Open "Document Root" folder "htdocs" and create new folder inside of "htdocs" with name for eg: "coolsite"
5) Download WordPress -> https://wordpress.org/download/
6) Unzip WordPress.zip file and copy all files from wordpress folder (wp-admin, wp-content, eg.) to created folder in step #4
7) Find and remember "Apache Port"  -> Open MAMP -> Preferences  for eg("80")
8) Open MAMP -> Start Servers
9) Open Web Browser and go to following url:  localhost:<Apache Port>/<Created folder in step #4    On my side it looks like this: "localhost:80/coolsite"
