#Selenium Test Environment with Angular UI Calendar application

###Setup
1. In the directory for your project "git clone https://github.com/mcherryleigh/testenv-angular-ui-calendar.git"
1. cd into cloned folder
1. In your terminal window "docker-compose up -d"
1. When docker is done building and starting the containers you will have One container for chrome/selenium, one for firefox/selenium, and a third with the calendar application.

###Where's the calendar?
By default, the calendar application will be available on 192.168.99.100:8000 in a browser.

###Using Selenium
* Point your Selenium script or the config file for your test suite at the selenium host 192.168.99.100:4444 (4445 for firefox)
* VNC is available at port 5900 for chrome and 5901 for firefox.

###Warnings
* If ports 4444, 4445, 5900, 5901, 8000 are occupied by other containers docker-compose up will fail