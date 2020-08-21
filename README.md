# js-plugin-template
Template for js plugin project.

## Installation
```
npm i
```

## Building
Build js bundle from `src/index.js`.
```
npm run build            
```

## Usage plugin outside

#### Full Bundle
```js
import plugin from 'js-plugin-template/dist/index.js'

plugin.logText('text') // print 'text' in console 
```

### Individual methods
```js
import { logText } from 'js-plugin-template/dist/index.js'

logText('text') // print 'text' in console 
```
