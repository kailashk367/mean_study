29 OCT 2017 - Mean stack installation - 

Install- NODE
npm init

Install- BOWER  (Manage front end dependcies) It is deprcated so install yarn
/*npm install -g bower*/
npm install -g yarn 
npm install -g webpack 

install grunt
npm install -g grunt-cli

to test grunt is working or not

create test folder and run command npm install grunt

install yeoman YO genrator
npm install -g yo
run cmd ad adminstror and run
IF EXIST C:\Users\<username>\AppData\Roaming\npm SET PATH=%PATH%;C:\Users\<username>\AppData\Roaming\npm


Yo generator helps us to install meanjs installer
npm install -g generator-meanjs

use older version for study
npm install -g generator-meanjs@0.1.12

Now open any directory and run yo meanjs command you will get all code base.
run command yo meanjs

install ruby

install sass
gem install sass

install grunt
install grunt-contrib-sass


generat frontend run- grunt build

now you need start database mongodb
create 1 folder on root db open one more CMD box
run command mongod --dbpath db (folder name).
O/P - port started 1279

aftre this you need to run grunt for open website.
O/P - means server started on 3000


Create folder to site
-mean_study
--src

run gerator in src folder
