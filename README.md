# AngularJS / Jade / Sass-Compass - Jekyll like for Yeoman

This is a skeleton for Yeoman with :

- a pimped Gruntfile for Jade template engine
- a little example about template inheritance (using a layout) and using locals (variables)
- no .html in app/ folders, only .jade, by using the magic `temp/` folder

**BUT DONT USE IT** Yeoman is under heavy changes (going to v.1..), this repo will be updated with Yeoman (Yo) v1. Some features are missing (jade templates are not compiled when launching yeoman server, livereload seems gone :/ and other little bugs) So I will spend more time on it when Yo will be stable !

Be kept informed of the transition : [Yeoman wiki](https://github.com/yeoman/yeoman/wiki)

## Jade 

Jade is very powerfull (nice markup, nice plugins with ST2, nice template inheritance)

- Jade documentation : [Jade doc](https://github.com/visionmedia/jade)
- Jade integration with Grunt : [grunt-jade](https://github.com/phated/grunt-jade)
	- Plugin to compile jade into HTML or JS functions
	- Able to assign locals (can be used for specifying configuration variables)	

