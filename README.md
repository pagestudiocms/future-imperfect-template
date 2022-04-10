# Pagestudio Future Imperfect Template

A Bootstrap and PageStudio version of the "Future Imperfect" theme by [HTML5 UP](https://html5up.net/).

## Getting Started 

**Repository Structure**

* **build** - A PageStudio ready template, complete with [template](http://developers.pagestudiocms.com/general/themes.html) tags
* **demo** - Sample pages complete with demo images
* **src** - The source files used to build the template, i.e. scss, js... pre-compiled files
* **theme** - The original theme by [HTML5 UP](https://html5up.net/)


## Dependencies 

* **NodeJS**
* **@pagestudiocms/pagestudio-template-development-server** NodeJS command line tool that sets up a development server on your computer.
* **@pagestudiocms/create-scss** Provides the SCSS framework (pre-defined styles on top of Twitter Bootstrap). 

Built on Bootstrap 3.3.7 and the [Studio Template Framework](https://github.com/pagestudiocms/studio-template-framework).

## Installation

- You need Node.js to be installed on your system. You can download Node.js and follow the instructions on how to do that on [nodejs.org](http://nodejs.org/);
- Clone or download this repository;
- Open your terminal;
- With the command line go to the folder you just cloned/downloaded and run;

```
npm install
```

## Usage

To start the NodeJS powered [pagestudio-template-development-server](https://github.com/pagestudiocms/pagestudio-template-development-server) with live SASS compilation, type:

***Note:*** Use this while developing your HTML, SCSS, and JS code. Run the **build** command (`sass:build`) to package your template and ready it for production. This will minify the `style.css` file and save it to the `build/css` folder.

```
npm run start
```
Then go to the browser and access http://localhost:9000/.

<br> 

To start your server and preview the contents of the demo folder without live scss compilation, run: 

```
npm run start-server
```

Then go to the browser and access http://localhost:9000/.

<br>

To build (or compile) your SCSS code, that is taking it from the `src` folder to `build/assets/css/` folder, run:

***Note:*** Use this to package your template SCSS and ready it for production.

```
npm run sass:build
```


## Acknowledgments

* Thank you to [HTML5 UP](https://html5up.net/) for this awesome template