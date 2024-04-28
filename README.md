# react-load-animations-plus

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Pure CSS animations as ready-to-use components for React.js.

## Installation

```bash
npm install react-load-animations-plus
```


## Demo

### _Click [here](https://react-load-animations-plus-website.vercel.app/) for the demo page that illustrates all the available loading animations_


## Attributes


| <div align ="center">Name </div> | <div align = "center">Description</div>                                              |
| -------------------------------- | ------------------------------------------------------------------------------------ |
| `color`                          | Color of the spinner. Insert the color or the color code in quotes. Black by default |


## Importing the Loaders


> ### _Replace `LoaderName` with the actual name of the loader. Visit the [demo](https://react-load-animations-plus-website.vercel.app/) page to see all the available loaders._


```javascript
import { LoaderName } from "react-load-animations-plus";
```


## Example


> ### _Given below is a simple implementation of the package._


```javascript
import { CircleLoader } from "react-load-animations-plus";

function App() {
  return (
    <>
      <CircleLoader color="Aqua" />
    </>
  );
}

export default App;
```
# License
This project is licensed under [MIT License](https://github.com/amitguria/react-load-animations-plus?tab=MIT-1-ov-file).

# Contribution
Contributions are welcome!
