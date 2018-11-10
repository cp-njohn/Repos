# Repos
Download the Repo
set path ../Projects/TestSuite/test-suite to terminal
  $cd ../Projects/TestSuite/test-suite to terminal
run npm install, whicj will install all the dependencies
  $ npm install
Start prject by run below command, tha will start the service on port "loaclhost:3000" 
  $nmp start
To start electron standalone app, run bwlow command from another terminal instance
  $electron .
To kill the service run on port 3000 run below command from terminal
  $lsof -nti:3004 | xargs kill -9
