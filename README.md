# Getting Started With ember-cli

This is an [ember-cli](http://www.ember-cli.com/) implementation of [TodoMVC](http://todomvc.com/).

Each commit corresponds to a single step in the Ember [Getting Started](http://guides.emberjs.com/v1.10.0/getting-started/) guide.

Commit descriptions include any corresponding [ember-cli generator](http://www.ember-cli.com/#generators-and-blueprints) and [addon](http://www.emberaddons.com/) install commands.

### Initial Commit from Ember CLI v0.2.0

`ember new todomvc-embercli`

View this step on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/748603666dd6856fec7bcfa0c82abac886688c54)
    

### Create static mockup

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/creating-a-static-mockup/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/a17bdec219568f59c3226226bcd7933f1fb04cd4)

### Add the first route and template

`ember g route todos --type resource --path '/'`

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/adding-a-route-and-template/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/fb670bced74954ba9d9c76bfe0d02e033e2480aa)

### Model data

`ember g model todo title:string isCompleted:boolean`

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/modeling-data/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/f84ddf121ff435422e0f860e290a13af604cf6b6)
    
### Use fixtures

```
ember g adapter application
```
**NOTE:** The adapter should extend `DS.FixtureAdapter` rather than `DS.RESTAdapter`

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/using-fixtures/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/22453817e1c1e367be794be0aba0405af7bf328b)
    
### Display model data

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/displaying-model-data/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/9dd594f417b65812bc32c91fec60652a664b7d8a)

### Display a model's complete state

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/displaying-a-models-completeness/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/43ab2f26e52e9ad09947eef72a6eec66a054a79f)

### Create a new model

`ember g controller todos`

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/creating-a-new-model/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/ccbc067896faeab4026d0e9ccf39f23411397421)
    
### Mark a model as complete or incomplete

```
ember g controller todo
```

**NOTE:** The controller should extend `Ember.ObjectController` rather than `Ember.Controller`

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/marking-a-model-as-complete-incomplete/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/f96776de82de2dff45bad90707a85ddad39c0d98)

### Display the number of incomplete todos

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/displaying-the-number-of-incomplete-todos/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/9156092665e44de2803b5746c9fb22b68ae0d75b)

### Toggle between showing and editing states

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/toggle-todo-editing-state/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/ae3f025f47d0cf053159379d25516a8bb3206e77)

### Accept edits

```
ember g component edit-todo
rm app/templates/components/edit-todo.hbs
```

**NOTE:** The component should extend `Ember.TextField` rather than `Ember.Component`

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/accepting-edits/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/00ce0d995ac94a40bbc1f33059027e0b93627397)

### Delete a model

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/deleting-todos/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/b70bc845cdc1ab2da120d277b4d5fb3b5610b236)

### Add child routes

`ember g template todos/index`

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/adding-child-routes/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/da657ebb7f7e7bac2a976d4756e2dcdafb38c094)

### Transition to show only incomplete todos

```
ember g route todos/active
rm app/templates/todos/active.hbs
```

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/show-only-incomplete-todos/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/9ba333fe2eb2e5586862039daa5259b86b60f9dd)

### Transition to show only complete todos

```
ember g route todos/completed
rm app/templates/todos/completed.hbs
```

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/show-only-complete-todos/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/2a3ef1c2b2cdd808c42eafbbf12bd3c4a22b6a8e)

### Transition back to show all todos

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/show-all-todos-again/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/2de790d9b44e04a3cf451a09acd2efa02a54bf96)

### Display a button to remove all completed todos

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/display-a-button-to-remove-completed-todos/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/3b58db01ea8b8acbac5964310711cfd1ed3c14ff)

### Indicate when all todos are complete

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/show-when-all-todos-are-complete/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/da7b50e18457618cbf21e73626800ca4a3192560)

### Toggle all todos between complete and incomplete

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/toggle-all-todos/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/9e0525b2e9eb1a43afbeffa7d8d73357bdc1e214)

### Replace the fixture adapter with another adapter

`npm install --save-dev ember-localstorage-adapter`

View this step in the [Ember.js Guide](http://guides.emberjs.com/v1.10.0/getting-started/using-other-adapters/) or on [GitHub](https://github.com/chrislopresto/todomvc-embercli/commit/d92f3579fcb82c5df762ef3b424d3cc5cdc768cb)

## Walkthrough

Check out [Ryan LaBouve's screencast](https://youtu.be/tonV3G2cPrA) for a walkthrough of the entire process. He explains each step thoroughly and does not use any generators along the way.

[![](http://img.youtube.com/vi/tonV3G2cPrA/0.jpg)](http://www.youtube.com/watch?v=tonV3G2cPrA)

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://www.ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone <repository-url>` this repository
* change into the new directory
* `npm install`
* `bower install`

## Running / Development

* `ember server`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](http://www.ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

