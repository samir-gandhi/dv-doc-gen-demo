# Error Message - Show Error From PingOne
## Configuration
ID:  qz2aml0p13

Type: CONNECTION 

CapabilityName: customErrorMessage






### Additional Properties
errorConnector
```json 
[
  {
    "children": [
      {
        "text": ""
      },
      {
        "text": ""
      },
      {
        "type": "link",
        "src": "functions.svg",
        "url": "updatedErrorMessage",
        "data": "{{local.f93pbyvrj2.payload.output.updatedErrorMessage}}",
        "tooltip": "{{local.f93pbyvrj2.payload.output.updatedErrorMessage}}",
        "children": [
          {
            "text": "updatedErrorMessage"
          }
        ]
      },
      {
        "text": ""
      }
    ]
  }
]
```




