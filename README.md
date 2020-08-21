# js-plugin-template
Template for js plugin project.

## Installation
```
npm i -D @dbetka/js-plugin-template
```

## Building
Build js bundle from `src/index.js`.
```
npm run build            
```

## Usage plugin outside

#### Full Bundle
```js
import plugin from '@dbetka/js-plugin-template'

plugin.logText('text') // print 'text' in console 
```

### Individual methods
```js
import { logText } from '@dbetka/js-plugin-template'

logText('text') // print 'text' in console 
```
