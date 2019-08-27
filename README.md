# interview-exercise
## requisites
- node: 10+
- npm: 6.10.0
- yarn: 1.17.3
- git: 2.20.1
- docker: 19.03.1
- docker-compose: 1.24.1

## Installation

### Install Meta

npm install -g meta

yarn global add meta

### Clone Management Repo

git clone git@github.com:tientnvn/interview-exercise.git

### Checkout All code

cd interview-exercise/
meta git update

## Run code

### Run code with local image

docker-compose up --build -d

### Or run code with pre-build image

docker-compose -f docker-compose-prod.yml up --build -d

## Test 

### View UI to verify
After running code, Access link: http://localhost:5001 

### Run API test
Import Postman collection: InterviewExercise.postman_collection.json
Choose Runner, select collection to run the test

### Run Unit test

cd backend

yarn install

yarn test



