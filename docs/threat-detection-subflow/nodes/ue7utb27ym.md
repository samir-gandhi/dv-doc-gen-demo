# Http - Error Message
## Configuration
ID:  ue7utb27ym

Type: CONNECTION 

CapabilityName: customHTMLTemplate

### Settings
| Setting | Value  |
| :------------------------ | ---------------------------------------- |
| Node Background Color | #ffc8c1ff | 

| Node Description | Configuration value not set error | 


## Custom HTML
```<div
  class="bg-light d-flex flex-column justify-content-center align-items-center position-absolute top-0 start-0 bottom-0 end-0 overflow-auto">
  <div style="max-width: 400px; min-width: 400px; width: 100%">
    <div class="card shadow mb-5">
      <div class="card-body p-5 d-flex flex-column">
        <img class="companyLogo align-self-center mb-5" alt="{{global.variables.companyName}}" />
        <h1 class="text-center mb-4">Flow Configuration Error</h1>
        <p class="text-muted text-center">{{errorConnector}}</p>
      </div>
    </div>
  </div>
</div>
```



### Additional Properties
errorConnector
```json 
[
  {
    "children": [
      {
        "text": "Unable to execute the flow due to missing parameter values."
      }
    ]
  }
]
```


formFieldsList
```
```


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
		}
	}
}
```


sktemplate
```string 

```


validationRules
```
```




