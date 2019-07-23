# Webpage_Translator_Using_Angular_JSON
# Description:
Company(Hashworks IT Services Private Limited)_Internship_Project.

Download all files and put it in one folder. After that open that folder on Visual Studio Code editor and install Node modules with help of "npm install" command. Then, comiple that project using "ng serve" command. Finally, open it on your favorite browser using http://localhost:4200 url.

Technology Used: HTML/HTML5, CSS/CSS3, Bootstrap 4, Angular 4, JSON.

Duration: Dec, 2018 to Jan, 2019.

# Procedure:
First thing you have to do create an angular project using "ng new 'project name' " command and for creating components using "ng g c 'component name' " command. Then, Install and load ngx-translate using "'npm install @ngx-translate/core --save'
'npm install @ngx-translate/http-loader'" command.

Import the necessary modules into app.module.ts : Add a function, that returns a “TranslateHttpLoader”. In this case the HttpLoaderFactory function we create, returns a Object that can load Translations using Http and .json. Then, need to import our modules into the @NgModule, this is the import that tells Angular to load this Module into your AppModule. Now, In “app.component.ts” init the “TranslateService”, import the TranslateService: Then inside the AppComponent Class we inject the service and define our default language and add a function to switch the language.

Now create translation files inside the assets/i18n folder: These are simple .json files that will be loaded by “TranslateHttpLoader”, created in “app.module.ts”. In app.component.html created four button with different language translater name and inside that button tag, created one onclick function and loop language element to each items when button translate clicked. After that attach language switcher function that we saw above in app.component.ts to a button. In this case create a button for each language and call the switchLanguage() function with the matching language key.

As mentioned before, sometimes have sentences to that contain variable and a user object with age and name inside the “app.component.ts”, and we want to translate a sentence that will contain this values: because we pass this object into the “translate”.

And every thing design with HTML/HTML5 tags and for style used CSS/CSS3 properties.

Finally, start the application using "ng serve" command.
 
