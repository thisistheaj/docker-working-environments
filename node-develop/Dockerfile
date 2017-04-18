FROM node
RUN apt-get -y update
RUN apt-get install -y vim

RUN npm install -g n typescript typings @angular/cli http-server express-generator sails yo gulp-cli grunt-cli bower forever mocha jasmine protractor

RUN apt-get install -y ruby-full
RUN gem install sass

CMD bash
