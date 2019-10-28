Happy holiday

[![npm version](https://img.shields.io/npm/v/happy-holiday.svg?style=flat-square)](https://www.npmjs.com/package/happy-holiday) 
[![npm downloads](https://img.shields.io/npm/dm/happy-holiday.svg?style=flat-square)](https://www.npmjs.com/package/happy-holiday) 
![NPM license](https://img.shields.io/npm/l/happy-holiday.svg?style=flat)
[![NPM total downloads](https://img.shields.io/npm/dt/happy-holiday.svg?style=flat)](https://npmcharts.com/compare/happy-holiday?minimal=true)

A libriary with no dependencies which adds a holiday's image to the site's logo.🎉

This is how it looks with default create-react-app logo:

<img alt="result" src="https://annmirosh.github.io/happy-holiday/images/result.png" height="100px">

## Getting started

Install `happy-holiday` using npm.

```
npm install happy-holiday --save
```

Import happyHoliday function and pass your property:

```
happyHoliday();     // with default options
```

Or download the script file from GitHib and add it to the page via `<script>` tag:

```<script src="dist/happy-holiday.js" type="text/javascript"></script>```

After it the global function `happyHoliday` will be available.

## Usage:

```happyHoliday();     // with default options```  

 or

```happyHoliday({});   // pass your options ```

## Options

```
{
  holiday: 'christmas',                      // "christmas" or "halloween"  (defult is "christmas")
  width: '50px',                             // image width
  height: '50px',                            // image width
  top: '32px',                               // image top position
  left: '32px',                              // image left position
  position: 'absolute,                       // image position
  src: ''                                    // set up your own image for any holiday
}
```

All options are optional. If no options are passed, default options will be applied.

## License

MIT