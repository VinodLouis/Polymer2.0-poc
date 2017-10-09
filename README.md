# \<Polymer2-0-poc\>

Weater forecasting

## Built on 
1. Polymer2.0
2. Web-components
3. ES6
4. HTML/CSS
5. OPEN data API


Application is live at [DEMO](http://www.vinodlouis.com/demos/weather-forecast)
## Runnig the Application

GLobal dependency on [Polymer CLI](https://www.npmjs.com/package/polymer-cli) as its used as development/testing server. The other libraries depedency are listed in bower.json file

1. Clone the repo
2. Do an `bower install`
3. serve via `polymer serve`
4. If all goes well application will be running on http://localhost:8081.


## Building  Application

```
$ polymer build
```

The buid configurations are written in polymer.json file. once builded can be checked via 
```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run application's test suite locally.


## Improvements

1. Design is currently not good just collapsible sort of instead should have been some table or carousel.
2. If Visualization is thought of it would be interesting to convert this data to chart of time series.
3. Unit test cases are incomplete as of now.
