# Error Message - Check if MFA is Enabled.
## Configuration
ID:  rs2jbqnsry

Type: CONNECTION 

CapabilityName: customErrorMessage

### Settings
| Setting | Value  |
| :------------------------ | ---------------------------------------- |
| Node Description | This check is done from Passwordless user and hence MFA has to be enabled | 





### Additional Properties
errorCode
```string 
400
```


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
        "text": "An error has occurred. Contact Adminsitrator"
      }
    ]
  }
]
```




