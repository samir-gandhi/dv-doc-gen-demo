# Functions - Check For User Consent?
## Configuration
ID:  6x74clj9zm

Type: CONNECTION 

CapabilityName: AEqualsB

### Settings
| Setting | Value  |
| :------------------------ | ---------------------------------------- |
| Node Description | If there is the need to check if user has consent before directing user to agreement | 





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
        "src": "auth.svg",
        "url": "checkRequired",
        "data": "{{global.parameters.checkRequired}}",
        "tooltip": "{{global.parameters.checkRequired}}",
        "children": [
          {
            "text": "checkRequired"
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


rightValueB
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


type
```string 
boolean
```





### Position

#### Previous Nodes
| Node Title | Node ID |
| :------------- | ------------ |
| EVAL | [6xfm9lpclg](./6xfm9lpclg.md) | 
 
 #### Future Nodes
| Node Title | Node ID |
| :------------- | ------------ |
| Evaluator |[prjjhhmndv](./prjjhhmndv.md) | 