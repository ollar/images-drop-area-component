images-drop-area-component
==============================================================================

Images and filed dropping sensitive area

Installation
------------------------------------------------------------------------------

```
ember install images-drop-area-component
```


Usage
------------------------------------------------------------------------------

```
{{#images-drop-area uploadImage=(action 'uploadImage')}}
    ...some html...
{{/images-drop-area}}
```

'uploadImage' - action to evaluate on drop

Contributing
------------------------------------------------------------------------------

### Installation

* `git clone <repository-url>`
* `cd images-drop-area-component`
* `npm install`

### Linting

* `npm run lint:js`
* `npm run lint:js -- --fix`

### Running tests

* `ember test` – Runs the test suite on the current Ember version
* `ember test --server` – Runs the test suite in "watch mode"
* `ember try:each` – Runs the test suite against multiple Ember versions

### Running the dummy application

* `ember serve`
* Visit the dummy application at [http://localhost:4200](http://localhost:4200).

For more information on using ember-cli, visit [https://ember-cli.com/](https://ember-cli.com/).

License
------------------------------------------------------------------------------

This project is licensed under the [MIT License](LICENSE.md).
