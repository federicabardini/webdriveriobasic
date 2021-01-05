## Prerequirements to run test on Selenoid Docker container

- Docker installed

- Start Selenoid docker container like this
  docker run --rm --name selenoid -p 4444:4444 selenoid/vnc_chrome:87.0

## Run tests

Write, through command line, the following command 
  npm run test 
to run test on local machine

or
  npm run testci
to run test on Selenoid
