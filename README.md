# js-plugin-template
Template for js plugin project.

## Installation
```
npm i
```

## Building
Build js bundle from `src/index.js` to `dist/index.js`.
```
npm run build            
```

## Usage plugin outside

#### Full Bundle
```js
import plugin from 'js-plugin-template' // js-plugin-template is path to plugin directory

plugin.logText('text') // print 'text' in console 
```

### Individual methods
```js
import { logText } from 'js-plugin-template' // js-plugin-template is path to plugin directory

logText('text') // print 'text' in console 
```
