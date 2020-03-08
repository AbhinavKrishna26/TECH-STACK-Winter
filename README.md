Project Title
# vue-todo


Getting Started
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).




Prerequisites

$ npm install vue

After installing required packages you can use “vue” command globally and create new project. To test the installation is successfully finished run the following command:

vue --version

To create new project we will run this command vue create “project_name” in appropriate directory for your wishes. Let’s start by creating a new project by marking the project’s name as vue-app.

vue create vue-app


At this time, you will face an appearance like below.

Vue CLI v3.5.1
? Please pick a preset:
❯ default (babel, eslint)
Manually select features

select default to go with the predefined settings

The main folder to write Vue codes is “src” and there are automatically created Vue components inside of it. Inside this folder all Vue operations will be done and then compiled to the form of code which can be understood by browsers. If you open file named as package.json in root directory you can see there are 3 command line option to be able run from terminal: 


serve — start development server on localhost to see code changes live


build — compress and build for production


lint — analyze dangerous scripts and coding style

Running the tests:

to run the vue app

 change current directory to the root directory of newly created Vue project then run command : npm run serve 
 
 the foloowing message will be displayed after performing the above command
 App running at:
- Local:   http://localhost:8080/
- Network: http://192.168.1.188:8080/



Enter the link (http://localhost:8080/) into your browser.

the  main.js file holds the following data

import Vue from 'vue'
import App from './App.vue'
new Vue({
   render: h => h(App),
}).$mount('#app')


the vue app basically consists of three sections
1st the template section 
2nd the script section 
and 3rd the style section







Authors
Abhinav Krishna

Acknowledgments

special mention to a youtube video vue in 65 mins 
css animate 
csszen garden

































