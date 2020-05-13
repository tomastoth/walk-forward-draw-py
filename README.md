# Walk forward draw

### Simple jupyter notebook for  comparing in sample equities with their out of sample part

### Replace data.json with your file that contains the equity changes next to the walk-forward.ipynb file for it to work.

### data.json format:
```
{
    "equityChanges":
            {"in":
                [[-5.0,10.0,-10.0,5.0,10.0,5.0,10.0],
                [-5.0,10.0,-10.0,5.0,10.0,5.0,10.0]],
            "out":
                [[-2.0,5.0,7.0,-5.0],
                [-2.0,5.0,7.0,-5.0]]},
            "startingEquity":
            10000.0
}
```