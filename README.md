# json-combine

A Polymer Element that combines two JSON objects into a single JSON object.

### Example
```html
<json-combine
  data-in1="[[dataIn1]]"
  data-in2="[[dataIn2]]"
  data-out="{{dataOut}}"
  combine-function="[[transform]]">
</json-combine>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

