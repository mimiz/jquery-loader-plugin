Jquery Loader Plugin
====================

 For usage, visit : http://www.mimiz.fr/en/jquery-loader-plugin/

 And for a demo : http://demos.mimiz.fr/jquery/loader

## Usage :

The usage is quite simple ...

To open the loader, use this

````javascript
$.loader({
   content:'Loading ...'
});
````

And to close the loader :

````javascript
$.loader("close");
````

### Options

* **content** 	: HTML Code, the content of the popin. Default is : ````'<div>Loading …</div>````
* **className** : the CSS class name for the loader. Default is : _loader_
* **id** : set the id of the loader. Default is _jquery-loader_
* **height** : set the height of the popin in pixels. Default is _60_
* **width** : set the width of the popin in pixels. Default is _200_
* **zIndex** : set the z-index of the popup. Default is _30000_
* **background** : set the background opacity and the id of the background. Default is ````{opacity:0.4, id:’jquery-loader-background’ }````

## Development :

 For helping in development, you will need to have node.js installed and, after forking and cloning, in the root directory of the project run the folowwing commands :

````
npm install
bower install
grunt test
grunt
````
