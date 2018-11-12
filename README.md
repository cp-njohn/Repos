# Repos
1. Download the Repo
2. Set path ../Projects/TestSuite/test-suite to terminal
    $cd ../Projects/TestSuite/test-suite to terminal
3. run npm install, whicj will install all the dependencies -> $ npm install
4. Start project by run command, that will start the service on port "loaclhost:3000"  -> $nmp start
5. To start electron standalone app, run bwlow command from another terminal instance -> $electron .
    
Note: To kill the service run on port 3000 run the command from terminal -> $lsof -nti:3004 | xargs kill -9
