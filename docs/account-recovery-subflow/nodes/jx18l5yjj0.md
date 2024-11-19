# Error Message - Invalid password
## Configuration
ID:  jx18l5yjj0

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
        "data": "{{local.5vhs0j1lcd.payload.output.updatedErrorMessage}}",
        "tooltip": "{{local.5vhs0j1lcd.payload.output.updatedErrorMessage}}",
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
      },
      {
        "type": "link",
        "src": "pingIdentity.svg",
        "url": "details",
        "data": "{{local.p7gnqv4r4t.payload.error.details}}",
        "tooltip": "{{local.p7gnqv4r4t.payload.error.details}}",
        "children": [
          {
            "text": "details"
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




