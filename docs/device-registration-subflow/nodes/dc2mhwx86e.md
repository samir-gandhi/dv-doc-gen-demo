# Node - Create OTP Device
## Configuration
ID:  dc2mhwx86e

Type: CONNECTION 

CapabilityName: startNode






### Additional Properties
inputSchema
```json 
{
	"type": "object",
	"properties": {
		"deviceType": {
			"type": "string",
			"displayName": "deviceType",
			"preferredControlType": "textField",
			"enableParameters": true,
			"propertyName": "deviceType"
		},
		"phone": {
			"type": "string",
			"displayName": "phone",
			"preferredControlType": "textField",
			"enableParameters": true,
			"propertyName": "phone"
		},
		"email": {
			"type": "string",
			"displayName": "email",
			"preferredControlType": "textField",
			"enableParameters": true,
			"propertyName": "email"
		},
		"usableDevices": {
			"type": "array",
			"displayName": "Usable Devices",
			"preferredControlType": "textField",
			"enableParameters": true,
			"propertyName": "usableDevices"
		},
		"rpid": {
			"type": "string",
			"displayName": "rpid",
			"preferredControlType": "textField",
			"enableParameters": true,
			"propertyName": "rpid"
		}
	}
}
```




