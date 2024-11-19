# Node - Return Error
## Configuration
ID:  cl9ugbu07r

Type: CONNECTION 

CapabilityName: startNode

### Settings
| Setting | Value  |
| :------------------------ | ---------------------------------------- |
| Node Description | Redirect back to requesting resource (error) | 





### Additional Properties
inputSchema
```json 
{
	"type": "object",
	"properties": {
		"errorConnector": {
			"type": "string",
			"displayName": "Error Message",
			"preferredControlType": "textField",
			"enableParameters": true,
			"propertyName": "errorConnector"
		},
        "flowMethod": {
			"type":"string",
            "displayName": "flowMethod",
            "preferredControlType": "textField",
            "enableParameters": true,
            "propertyName": "flowMethod"
        }
	}
}
```




