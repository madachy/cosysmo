# cosysmo
se-lib Constructive Systems Engineering Cost Model (COSYSMO)

Use per the following.

```
# test case
size = 628 # equivalent nominal requirements
cost_factors = {
    "Requirements Understanding": "High",
    "Technology Risk": "High",
    "Process Capability": "High"
}

effort = cosysmo(628, cost_factors)
print(f'{effort=}')
```

