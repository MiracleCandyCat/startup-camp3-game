2013.10.05: HTML5 & JavaScript 應用與雲端服務整合開發


## Stage 1

Refactor 912492d7adb5c4368c1496af87a632f694f30b62

- Move JavaScript code to main.chat.js
- Using JavaScript closure (module)
- Using yepnope loader

## Stage 2

Mapping view and data

- Using key-value pairs (ViewModel): use JSON to present key-value data
- Using Backbone (fully application framework) for applying ViewModel, or
- Simple template library (eg. [jquery template](https://github.com/BorisMoore/jquery-tmpl))
- UI made easy: use Bootstrap CSS framework

## Stage 3

Application

- Use Bootstrap navbars
- Responsive design by Bootstrap

## Stage 4

Send data

- Use WebSocket send()
- Connect Open API: AJAX and RESTful
- Not use AJAX method: if so, either jQuery way or Backbone way is good
- Not use RESTful API: refactor URL query string to REST spec

# Stage 5

Going mobile

- Use PhoneGap: build.phonegap.com or Eclipse+PhoneGap
- Use viewport
- Use Mixins (LESS) to set media query of 'screen' height

# Stage 6

Using PhoneGap APIs

- Camera web app
