# PingOne Authentication - Redirect With Error Response
## Configuration
ID:  yr9tytff7

Type: CONNECTION 

CapabilityName: returnErrorResponseRedirect

### Settings
| Setting | Value  |
| :------------------------ | ---------------------------------------- |
| Node Background Color | #ffc8c1ff | 






### Additional Properties
customErrorFlag
```bool 
true
```


errorConnector
```string 
invalid_request
```


errorDescription
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
        "src": "teleport.svg",
        "url": "errorConnector",
        "data": "{{local.cl9ugbu07r.payload.output.errorConnector}}",
        "tooltip": "{{local.cl9ugbu07r.payload.output.errorConnector}}",
        "children": [
          {
            "text": "errorConnector"
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




