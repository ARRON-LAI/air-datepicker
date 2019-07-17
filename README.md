# Air Datepicker AMD

Lightweight customizable cross-browser jQuery datepicker, built with es5 and css-flexbox. Works in all modern desktop and mobile browsers (tested on Android 4.4+ and iOS8+).

Forked from http://t1m0n.name/air-datepicker/.
1. Refined it to support AMD
2. Bugfixing
3. New features like pair datepicker. (Datepicker with two selection panel)

[Comming features]
1. Accessibility (will support key press like 'tab', 'enter', 'esc')

![air pair clndr image](https://raw.githubusercontent.com/arronlai/air-datepicker-amd/master/docs/img/promo-img-pair-dp.png)

![air datepicker image](https://raw.githubusercontent.com/arronlai/air-datepicker-amd/master/docs/img/promo-img-time.png)

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
* [In English](http://arronlai.com/air-datepicker-amd/docs/)
* [In Russian](http://arronlai.com/air-datepicker-amd/docs/index-ru.html)

## Change log

### v3.0.0-alpha
* [New feature] Add another type of datepicker, double datepicker, which is a datepicker with two selection panel. With it user can view the start and end date at the same time when they want to choose some time longer than one month.
  ![air pair clndr image](https://raw.githubusercontent.com/arronlai/air-datepicker-amd/master/docs/img/promo-img-pair-dp.png)

* [Refine] Include gulp babel into build process.
* [Refine] Add inst to onChangeMonth callback
### v2.4.2
* trigger onChangeMonth function while change view from 'year' to 'month'.
### v2.4.1
* refine datepicker to update view when mouse leave datepicker content body, so that 'in-range' classes won't be preserved when the mouse is no longer hover on datepicker after selecting one date when 'range' = true.
### v2.4.0
* refine build tasks for i18n so that jQuery won't be assumed as global variable; fix the bug that disabled navigation button (prev/next) is still clickable when change style to 'visibility = visible'.
* 
### v2.3.0
* support AMD for datepicker.en.js; fix the bug that when 'showOtherMonths' = false and other-month cell is still clickable.
* 
### v2.2.4
* support AMD for body.js, datepicker.js, timepicker.js and navigation.js

