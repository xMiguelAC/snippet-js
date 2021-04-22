# snippet-js

Este es mi snippet personal donde lo estare preparando para trabajar mas rapido... algo asi como Emmet


{

	"Print to console": {
		"prefix": "clog",
		"body": [
			"console.log('$1');"
		],
		"description": "Log output to console"
	},

	"Print a function": {
		"prefix": "pfun",
		"body": [
			"function $1 (x, y) { code... };"
		],
		"description": "a simple function"
	},

	"Print an arrow function": {
		"prefix": "arrow",
		"body": [
			"const xxx = (parametro) => { code... };"
		],
		"description": "output an arrow function"
	},

	"output a class component": {
		"prefix": "classcomp",
		"body": [
		  "class Xxx extends React.Component{",
		  "  render() {",
		  "    return <h1> xxxx </h1>;",
		  "  }",
		  "}"
		],
		"description": "output a class component"
	  },

	  "componente funcional de React": {
		"prefix": "react-comp-f",
		"body": [
		  "import React, { useState } from \"react\";",
		  "",
		  "function Component () { ",
		  "    const [example, setExample] = useState(0);",
		  "",
		  "    return(",
		  "        <div>",
		  "            code ... ",
		  "        </div>",
		  "    );",
		  "}",
		  "",
		  "export default Component;"
		],
		"description": "componente funcional de React"
	  }
}

