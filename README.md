## Getting Started

```
$ npm install -g yo                                # Install Yeoman (if you don't have it yet)...
$ npm install -g generator-react-gulp-browserify   # ...then install this generator...
$ yo react-gulp-browserify                         # ...and run it.
```

If you chose to use sass, you'll need to install it with `gem install sass`.
If you find your css build results are empty, update your sass gem.

## Output folders 

scripts - /scripts  
styles - /styles  
fonts - /fonts  


Now, when everything is ready, run the watch task and begin to develop your React components.

```
$ gulp watch
```

How to run test?  
Currently, I prefer to run test tasks from npm. Please run this command.
```
$ npm test
```

After development, you can run this task to generate production code.
```
$ gulp build
```

## License

MIT
