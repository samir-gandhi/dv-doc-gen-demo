# Flow Connector - CIAM - Account Recovery 
## Configuration
ID:  5b7wgayb4e

Type: CONNECTION 

CapabilityName: startUiSubFlow






### Additional Properties
ciam_companyLogo
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
        "url": "flowCompanyLogo",
        "data": "{{local.4rjs3llu20.payload.output.flowCompanyLogo}}",
        "tooltip": "{{local.4rjs3llu20.payload.output.flowCompanyLogo}}",
        "children": [
          {
            "text": "flowCompanyLogo"
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


passwordRecovery
```json 
[
  {
    "children": [
      {
        "text": "true"
      }
    ]
  }
]
```





### Position

#### Previous Nodes
| Node Title | Node ID |
| :------------- | ------------ |
| EVAL | [rc315a9uh1](./rc315a9uh1.md) | 
 
 #### Future Nodes
| Node Title | Node ID |
| :------------- | ------------ |
| EVAL |[w9egwegsnj](./w9egwegsnj.md) | 