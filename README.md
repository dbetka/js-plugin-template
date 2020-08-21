# js-plugin-template
Template for js plugin project.

## Installation
```
npm i -D @dbetka/js-plugin-template
```

## Building
```
npm run build            Build js bundle from js and vue files.
```

## Usage outside of plugin

#### Full Bundle
```js
import VueAtomic from '@dbetka/vue-plugin-template'
import '@dbetka/vue-plugin-template/dist/index.css'

Vue.use(VueAtomic)
```

### Individual components
with default name
```js
import { OwnButton } from '@dbetka/vue-plugin-template'
import '@dbetka/vue-plugin-template/dist/own-button.css'

Vue.component(OwnButton.name, OwnButton) // component name is m-input
```
with own name
```js
import { OwnButton } from '@dbetka/vue-plugin-template'
import '@dbetka/vue-plugin-template/dist/own-button.css'

Vue.component('new-button', OwnButton) // component name is new-input
```

## Project maintenance 

Scripts used in `package.json` has own docs [here](scripts/README.md)
