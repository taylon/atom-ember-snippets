## Ember Snippets

Ember.js ES6 snippets for Atom editor (ex: ember-cli, ember-app-kit)

## Installation

Run the following command:

```sh
apm install ember-snippets
```

Then reload your Atom.


## Usage

#### Modules

- `active-adapter` ⇥
- `active-serializer` ⇥
- `adapter` ⇥
- `arr-controller` ⇥
- `component` ⇥
- `controller` ⇥
- `helper` ⇥
- `initializer` ⇥
- `mixin` ⇥
- `model` ⇥
- `object` ⇥
- `route` ⇥
- `serializer` ⇥
- `transform` ⇥
- `utility` ⇥
- `view` ⇥

Example output for `controller` ⇥

Javascript:
```js
import Ember from 'ember';

export default Ember.Controller.extend({
	// body
});
```

CoffeeScript:
```coffee
NameController = Ember.Controller.extend
	# body

`export default NameController`
```

#### Properties

Used inside Ember objects

- `property` ⇥
- `observer` ⇥
- `on` ⇥
- `actions` ⇥
- `alias` ⇥

Example output for `observer` ⇥

JavaScript:
```js
fooChanged: Ember.observer('foo', function() {
	// body
}),
```

CoffeeScript:
```coffee
fooChanged: Ember.observer 'foo', ->
	# body
```


#### Functions

- `find` ⇥
- `find-id` ⇥
- `logger-debug` ⇥
- `logger-error` ⇥
- `logger-info` ⇥
- `logger-log` ⇥
- `logger-warn` ⇥

Example output for `find` ⇥

JavaScript:
```js
this.store.find('post');
```

CoffeeScript:
```coffee
this.store.find 'post'
```

#### Enumerables

- `forEach` ⇥
- `filter` ⇥
- `filterBy` ⇥
- `map` ⇥
- `mapBy` ⇥
- `every` ⇥
- `isEvery` ⇥
- `some` ⇥
- `isAny` ⇥
- `toArray` ⇥
- `firstObject` ⇥
- `lastObject` ⇥

Example output for `isAny` ⇥

JavaScript:
```js
people.isAny('isHappy', true);
```

CoffeeScript:
```coffee
people.isAny 'isHappy', true
```
