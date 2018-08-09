# hw-form
Hashworks Forms

## Installation 
```sh
npm install hw-form --save
yarn add hw-form
bower install pluralize --save
```
## Usage
### Javascript
```javascript
var pluralise = require('hw-form');
var boys = pluralise.getPlural('Boy');
```
```sh
Output should be 'Boys'
```
### TypeScript
```typescript
import { getPlural } from 'hw-form';
console.log(getPlural('Goose'))
```
```sh
Output should be 'Geese'
```
### AMD
```javascript
define(function(require,exports,module){
  var pluralise = require('hw-form');
});
```
## Test 
```sh
npm run test
```