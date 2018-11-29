# Air Datepicker

Forked from http://t1m0n.name/air-datepicker/, refined it to support AMD and fixed some bugs. 

Lightweight customizable cross-browser jQuery datepicker, built with es5 and css-flexbox. Works in all modern desktop and mobile browsers (tested on Android 4.4+ and iOS8+).

![air datepicker image](https://github.com/t1m0n/air-datepicker/raw/master/docs/img/promo-img-time.png)

## Install

### npm
```
npm i --save air-datepicker-amd
```

## Usage
```javascript
$('.my-datepicker').datepicker([options])
```

## Demo and docs
* [In English](http://t1m0n.name/air-datepicker/docs/)
* [In Russian](http://t1m0n.name/air-datepicker/docs/index-ru.html)

## Change log

### v2.4.0
* refine build tasks for i18n so that jQuery won't be assumed as global variable; fix the bug that disabled navigation button (prev/next) is still clickable when change style to 'visibility = visible'.
* 
### v2.3.0
* support AMD for datepicker.en.js; fix the bug that when 'showOtherMonths' = false and other-month cell is still clickable.
* 
### v2.2.4
* support AMD for body.js, datepicker.js, timepicker.js and navigation.js

