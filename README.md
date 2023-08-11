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
1) [AMPPS](https://ampps.com/)
   - Pro
       - Easy to use
       - Many functionalities
       - Fewer steps to setup
   - Con
       - Not working on Latest Mac OS
       - May be not developed anymore
2) [Docker](https://docker.com/)
   - Pro
       - Very stable
       - Fewer steps to setup
   - Con
       - Docker knowledge
4) [LOCAL](https://localwp.com/)
   - Pro
       - Easy to use
       - Specifically for WordPress
   - Con
       - Behave differently for Windows and Mac
       - Extra step to connect to db with port
       - Extra step to access from a Docker
5) [MAMP](https://mamp.info/)
   - Pro
       - Easy to use
       - Stable
   - Con
       - None
__________________________________________________________________
# Running WordPress with MAMP
1) Download and install with all default settings [MAMP & MAMP PRO](https://www.mamp.info/en/downloads/)
2) Save "Document Root" folder path -> on the References from the top menu
3) Open "Document Root" folder "htdocs" and create new folder inside of "htdocs" with name for eg: "coolsite"
4) Download [WordPress](https://wordpress.org/download/)
5) Unzip WordPress.zip file and copy all files from wordpress folder (wp-admin, wp-content, eg.) to created folder in step #3
6) Find and remember "Apache Port"  -> Open MAMP -> Preferences  for eg("80")
7) Open MAMP -> Start Servers
8) Open Web Browser and go to following url:  localhost:<Apache Port>/<Created folder in step #4    On my side it looks like this: "localhost:80/coolsite"

# WordPress Installation Page
1) Select your language (eg. English)
2) Click "Lets go" on the next page
3) Find and remember "MySQL Port"  -> Open MAMP -> Preferences  for eg("80")
4) Download and Install [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
5) Open MySQL Workbench and Setup New Connection by clicking "+" button
6) Input some name in Connection Name field "MAMP"
7) Input port which we found in step #3
8) Click on "Test Connection" button and if ask password, than input "root" value
9) Click "OK" if successfull msg, and click "OK" again
10) Click on "MAMP" db and add new schema with same name which we specified in step #3 from previos paragraph "coolsite", click Apply, click Finish/Close
11) Go back to browser and Input Database Name which we specified in step #10 eg. "coolsite"
12) Input "root" in Username and Password fields
13) Click "Submit" button
14) Click "Run the installation" button
15) Specify Site Title -> for eg. "Cool Site" or smthing else
16) Specify username -> for eg. "admin"
17) Specify password -> for eg. "admin123"
18) Click "Confirm weak password" checkbox if it is present
19) Specify your email in email field
20) Click "Search engine visibility" checkbox and click "Install WordPress" button
21) Try to Login with user from step #16 and password from step #17
__________________________________________________________________
# Running WordPress with AMPPS
1) Download and install with all default settings [AMPPS](https://ampps.com/downloads/)
2) Please close MAMP when you try to run AMPPS
3) Start AMPPS and Click Home button
4) On the browser AMPSS page click "Blogs" from the left menu and install "WordPress"
5) Specify Site Name -> for eg. "Cool Site" or smthing else
6) Specify "Admin Username" -> for eg. "admin"
7) Specify "Admin Password" -> for eg. "admin123"
8) Scroll to the buttom and click "Install" button
9) Click on "Administrative URL"
__________________________________________________________________
