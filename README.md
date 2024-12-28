
# Angular Security with OAuth2 and Custom JWT

- Module Based implementation (auth, core, features, shared), Angular 11 with Bootstrap 5
- Custom register/login, password-reset included
- Public & Authenticated Pages, param based routing and form validations

## __Basic Setup - Main Structure:__

- __Auth Module__ : Login, Signup and authentication modules.
- __Core Module__ : Global Constants/Utils/Models, All Services, URL Constant etc. (anything global/abstract/core, and reusable tools/constant)
- __Feature Module__ : App specific components.   
__This App (Angular Sample Starter)__ : 
    - __Public Pages__ (publicy accessible related components)
    - __Dashboard__ (user dasboard, can be general or user specific. e.g Admin/Normal-User)
- __Shared Module__ : Generic Components that can be used anywhere (Buttons, Inputs, Loading, Icons, card-component etc. )


- __Additional Notes__:
    - _If App Code-Base Scales ?_ : Create or Modify feature/components/view under their own baseline module; _i.e create modules to group them_. 
        - Import modules only when required and use lazy loading.
    - _Need to add or test a new functionality ?_ : Create a seperate modules in root directory "/app", and use as required.
    - _Need custom css with component/section seperation ?_ : Create main folder "Styles" and other structure as required. Use SCSS file and import them into main styles.scss file. 

## # Initialized
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.5.

## # Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

```cmd
ng serve
```


## # Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
