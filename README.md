## react-native-infinite-scrollview
[![npm version](https://badge.fury.io/js/react-native-infinite-scrollview.svg)](https://www.npmjs.com/package/react-native-infinite-scrollview)
![react-native platform](https://img.shields.io/badge/platform-ios-blue.svg)

ScrollView with infinte paged scrolling (no looping). The number of pages rendered before and after current page can be customized. Pages are rendered when user scrolled.

### Content
- [Installation](#installation)
- [Examples](#examples)
- [API](#api)
- [Questions?](#questions)

### Installation
```bash
npm i react-native-infinite-scrollview --save
```

### Examples
Simple Calendar example included.
![react-native-infinite-scrollview demo](https://raw.githubusercontent.com/baspellis/react-native-infinite-scrollview/master/example/video/demo.gif)

### API
Component wraps ScrollView so all ScrollView properties are available.
- **renderPage** - Required - (Function) - Must return a component representing the page for the provided index.
- **offScreenPages** - Optional - (Integer) - Number of pages to render before and after the current page. Default is 1 (total 3 pages are rendered).
- **index** - Optional - (Integer) - Start the scrollview with this index. Default is 0 or toIndex whichever is greater.
- **toIndex** - Optional - (Integer) - Don't allow scrolling below this page index.
- **fromIndex** - Optional - (Integer) - Don't allow scrolling above this page index.
- **onPageIndexChange** - Optional - (Function) - Called when page index is changed (user scrolled).
- **forceUpdate** - Optional - (Number) - Forces render be called if it changes.

### Known issues
Currently only iOS is supported. Android support is coming.

### Questions?
Feel free to contact me via
- [Twitter](https://twitter.com/baspellis)

If you want to report a bug, please [submit an issue!](https://github.com/baspellis/react-native-infinite-scrollview/issues/new)
