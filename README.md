### React Study Group

# Hello World

Ejemplo simple con React


```
use react {
	use create-react-app to create project {
		install create-react-app {
			install npm
			$ npm install -g create-react-app
		}
		$ create-react-app hello-world
	}
}
to show hello world {
	define component to render into root target node
		create external component
			use react lib
				import React
			define class App
			define method render
		use external component
			import App from './App'	
}
```

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

