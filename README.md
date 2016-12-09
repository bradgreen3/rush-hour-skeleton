### Rush Hour

This application is a web traffic tracking and analysis tool using Ruby, 
Sinatra, and ActiveRecord. The process of gathering and receiving data 
(payloads) is simulated via curl requests. The application accepts the 
submission of payloads and analyzes the data submitted, displaying it through a 
HTML interface.

### Sinatra version
* 1.4.7

### Setup

* ```git clone https://github.com/bradgreen3/rush-hour-skeleton.git```
* Bundle gem file: ```bundle```
* Set up database: ```rake db:{create,migrate}```
* Populate/seed data: ```./test.sh```

### Run Test Suite

* ```rspec```

### Author
Brad Green
