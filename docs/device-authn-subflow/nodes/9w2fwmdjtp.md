# Error Message - PingOne Protect Risk ID is Empty/NULL
## Configuration
ID:  9w2fwmdjtp

Type: CONNECTION 

CapabilityName: customErrorMessage

### Settings
| Setting | Value  |
| :------------------------ | ---------------------------------------- |
| Node Description | Provide the Risk ID in "Invoke PingOne Protect Subflow" | 





### Additional Properties
errorConnector
```json 
[
  {
    "children": [
      {
        "text": "Error"
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
        "text": "Error Occurred. Contact Adminsitrator"
      }
    ]
  }
]
```




