# What I Learned

* You can easily find out what commands you can run (e.g. ```mocha```) by listing the contents of the hidden ```.bin``` folder in the ```node_modules``` folder.

## Shortcuts
I knew `npm run <scriptname>`, but never knew that:
* ```run``` is shorthand for ```run-script```
* There are various shortcuts for ```npm run-script test```:
    * ```npm run test```
    * ```npm test```
    * ```npm tst```
    * ```npm t```
* ```npm start``` is short for ```npm run start```

## Conventions
It's normal to have ```start```, ```stop``` and ```test``` scripts. Running ```restart``` will automatically run ```stop```, then ```start```, unless you define your own ```restart``` script, which will only do exactly what you specify.