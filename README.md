# button-link

A Polymer Element showing a stylized button that opens a link when clicked or tapped.

### Example
```html
<button-link
  link="http://link"
  target="_blank"
  text="Click Me"
  show>
</button-link>
```

### Styling

`<button-link>` provides the following custom properties and mixins for styling:

Custom property                  | Description                         | Default
---------------------------------|-------------------------------------|--------
`--button-link-background-color` | The background color of the button. | none

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower

### Testing

    Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

        npm install -g web-component-tester
        wct

### Demonstration & Documentation

    Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

        npm install -g polyserve
        polyserve

    bower install
