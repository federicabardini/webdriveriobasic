## Prerequirements to run test on Selenoid Docker container

- Docker installed

- Start Selenoid docker container like this
  docker run --rm --name selenoid -p 4444:4444 selenoid/vnc_chrome:87.0

## Run tests

Write, through command line, the following command 
 - npm run test 
to run test on local machine, both on Chrome and Firefox (local version installed on local machine)


Every push on the repo will trigger test run on GitHub CI on Chrome and Firefox last version (through Selenoid)
 - npm run testci
