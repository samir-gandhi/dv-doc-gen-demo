# Functions - Update Error Message
## Configuration
ID:  f93pbyvrj2

Type: CONNECTION 

CapabilityName: customFunction





### Output Schema
``` {
	"output": {
		"type": "object",
		"properties": {
			"updatedErrorMessage": {
				"type": "string"
			}
		}
	}
} 
```

### Additional Properties
code
```js 
// Write your code here
// Supported language: Javascript 
module.exports = a = async ({params}) => {
	let errorConnector = params.errorConnector;

	if (errorConnector === "phone: must be a well-formed phone number with a valid country code followed by a phone number") {
		errorConnector = "Enter a valid phone number, including the country code.";
	}

	return {&#39;updatedErrorMessage&#39;: errorConnector};
}
```


variableInputList
```
```





### Position

#### Previous Nodes
| Node Title | Node ID |
| :------------- | ------------ |
| EVAL | [2my7xaouma](./2my7xaouma.md) | 
 
 #### Future Nodes
| Node Title | Node ID |
| :------------- | ------------ |
| EVAL |[hqdb3y3i65](./hqdb3y3i65.md) | 