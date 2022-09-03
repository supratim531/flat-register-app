# flat-register-app ([Spring-Boot](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/) & [Angular](https://angular.io/docs))

### [Frontend](https://registerflat.netlify.app/ "see the UI deployment in netlify") and [Backend](https://registerflat.herokuapp.com/ "see the server deployment in heroku") of `Flat Register` Web Application
This is a simple application on flat registration based upon basic CRUD functionality #SpringAngular

## Test App in Local Server
```terminal
git clone https://github.com/supratim531/flat-register-app.git supratim-flat-register-app
```

### Run the `Spring-Boot` App from your `windows-terminal`
- Switch the directory
```bash
cd supratim-flat-register-app\flat-register-backend
```
- Run the spring application (After run this command the local backend server will serve by JVM)
```bash
mvn spring-boot:run
```

### Run the `Angular` App from your `windows-terminal`
- Switch the directory from different terminal
```bash
cd supratim-flat-register-app\flat-register-frontend
```
- Run the ng application (After run this command the default browser will open to serve the [angular app](http://localhost:4200 "By default Angular CLI ng serve command uses port 4200 to run the application in localhost"))
- `This command may takes some time`
```bash
npm install && ng s --o
```
