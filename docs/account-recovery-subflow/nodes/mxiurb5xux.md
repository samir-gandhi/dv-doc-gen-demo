# PingOne Notifications - Send email for threat detected
## Configuration
ID:  mxiurb5xux

Type: CONNECTION 

CapabilityName: sendEmail

### Settings
| Setting | Value  |
| :------------------------ | ---------------------------------------- |
| User ID |```[  {    "children": [      {        "text": ""      },      {        "text": ""      },      {        "type": "link",        "src": "pingIdentity.svg",        "url": "id",        "data": "{{local.g3ie4cp1z5.payload.output.matchedUser.id}}",        "tooltip": "{{local.g3ie4cp1z5.payload.output.matchedUser.id}}",        "children": [          {            "text": "id"          }        ]      },      {        "text": ""      }    ]  }] ```|
| Node Description | Email notification that user is blocked and disabled. | 





### Additional Properties
customTemplateVariant
```json 
{}
```


email
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
        "url": "email",
        "data": "{{local.g3ie4cp1z5.payload.output.matchedUser.email}}",
        "tooltip": "{{local.g3ie4cp1z5.payload.output.matchedUser.email}}",
        "children": [
          {
            "text": "email"
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


templateVariables
```
```


templateVariant
```string 
Threat Detected
```





### Position

#### Previous Nodes
| Node Title | Node ID |
| :------------- | ------------ |
| EVAL | [0gubix0onw](./0gubix0onw.md) | 
 
 #### Future Nodes
| Node Title | Node ID |
| :------------- | ------------ |
| EVAL |[jozexysssa](./jozexysssa.md) | 