# vue-highlight-text

> highlight text search with keyword

## Installation
```bash
# with yarn
yarn add vue-highlight-text

# with npm
npm install --save vue-highlight-text
```
## Usage
```js
import Vue from 'vue'
import HighlightText from './components/VueHighlightText'

Vue.component('HighlightText', HighlightText)
```

## In file vue
```html
<HighlightText :keyword="keyword" :sensitive="sensitive">{{msg}}</HighlightText>
```