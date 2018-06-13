## React Color Component

### Installation

`npm install --save react-color-square`

### How To Use

First import this component where you want to use it

`import ReactColorSquare from "react-color-square"`

Then just renders it

`<ReactColorSqaure />`

### Props

| _Prop_ |     _Description_     | _Default value_ |
| ------ | :-------------------: | :-------------: |
| color  | Sets background color |      blue       |
| width  |      Sets width       |       100       |
| height |      Sets height      |       100       |
| text   |    Sets inner text    |  empty string   |

### Example

```
import React, { Component } from "react";
import ReactColorSquare from "react-color-square";

class App extends Component {
  render() {
    return (
        <ReactColorSquare height={150} color="red" text="Hello World!" />
    );
  }
}

export default App;
```
