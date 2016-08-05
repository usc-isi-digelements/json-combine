# status-text

A polymer web component that combines two JSON objects into a single JSON object.

Example:
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
