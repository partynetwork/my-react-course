# Introduction

Use the full power of the modern JavaScript ecosystem – WebStorm’s got you covered! Enjoy the intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and the most popular frameworks.

### Support Language & Framework

Web

- Angular 1,2,4
- React
- Vue.js

Mobile

- Ionic
- Cordova
- React Native

Server

- Node.js
- Meteor

Desktop

- Electron

# Installation

- [ ] Download [WebStorm IDE](https://www.jetbrains.com/webstorm/download) 
- [ ] Download [NodeJs v8+](https://nodejs.org/en/)
- [ ] Download [Git](https://git-scm.com/)

# Appearance behavior

Go to menu File > Settings [CTR+ALT+S]

1. Editor
2. Plugins
3. Language & Framework

# Setup Todo App

Create React apps with no build configuration.

```javascript
$ yarn global add create-react-app <!--or--> npm install -g create-react-app
$ create-react-app todos
$ cd todos/ 
$ yarn add redux react-redux
$ yarn add jest jest-cli babel-jest enzyme react-test-renderer babel-preset-stage-0 identity-obj-proxy --dev
$ npm run start
```

Note: add this source to package.json

```json
"babel": {
    "presets": [
      "react",
      "es2015",
      "stage-0"
    ]
  }
```

Create jest configuration file for npm : jest.conf.json

```json
{
    "moduleNameMapper": {
    	"^.+\\.(css|scss|svg)": "identity-obj-proxy"
    }
  }
```

# Live Template

Create live template for easy setup component class

```javascript
import React,{Component} from 'react'
class $NAME$ extends Component {
  constructor(props) {
      super(props)
  }
  componentWillMount() {}
  componentDidMount() {}
  render() {
      return (
          <div>$END$</div>    
      )
  }
}
export default $NAME$
```

# Test Tools

# Git & VCS	

## Merge tools

