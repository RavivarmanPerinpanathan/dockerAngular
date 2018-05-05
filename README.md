# DockerAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.4.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Run these cmd's after downloaded from Github and after ng build

docker build -t angular5 .

## copy the Dockerfile from DockerFileToCopyInDistFolder and move to the dist folder

docker run -d --name "NAME" -p 8082:80 angular5

