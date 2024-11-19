# Functions - Risk Score from PingOne Protect
## Configuration
ID:  dpyuspmzna

Type: CONNECTION 

CapabilityName: AEqualsMultipleB

### Settings
| Setting | Value  |
| :------------------------ | ---------------------------------------- |
| Node Description | Branching based on risk score from PingOne Protect | 





### Additional Properties
leftValueA
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
        "src": "variable.svg",
        "url": "ciam_protectRiskLevel",
        "data": "{{global.variables.ciam_protectRiskLevel}}",
        "tooltip": "{{global.variables.ciam_protectRiskLevel}}",
        "children": [
          {
            "text": "ciam_protectRiskLevel"
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


rightValueMultiple
```
```





### Position

#### Previous Nodes
| Node Title | Node ID |
| :------------- | ------------ |
| EVAL | [vkiofgjsix](./vkiofgjsix.md) | 
 
 #### Future Nodes
| Node Title | Node ID |
| :------------- | ------------ |
| EVAL |[v7rng0sn5c](./v7rng0sn5c.md) | 