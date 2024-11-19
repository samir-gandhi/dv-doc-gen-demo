# Error Message - Invalid password
## Configuration
ID:  o5pe6jfpi5

Type: CONNECTION 

CapabilityName: customErrorMessage

### Settings
| Setting | Value  |
| :------------------------ | ---------------------------------------- |
| Node Description | An error occurred during account recovery | 





### Additional Properties
errorCode
```json 
[
  {
    "children": [
      {
        "text": "Invalid"
      }
    ]
  }
]
```


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
        "data": "{{local.awcyj6ng8l.payload.output.updatedErrorMessage}}",
        "tooltip": "{{local.awcyj6ng8l.payload.output.updatedErrorMessage}}",
        "children": [
          {
            "text": "updatedErrorMessage"
          }
        ]
      },
      {
        "text": ""
      },
      {
        "text": ""
      }
    ]
  }
]
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
      }
    ]
  }
]
```


errorReason
```json 
[
  {
    "children": [
      {
        "text": ""
      },
      {
        "text": ""
      }
    ]
  }
]
```




