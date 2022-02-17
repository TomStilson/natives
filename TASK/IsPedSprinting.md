---
ns: TASK
---
## IS_PED_SPRINTING

```c
// 0x57E457CD2C0FC168 0x4F3E0633
BOOL IS_PED_SPRINTING(Ped ped);
```
Is the ped given sprinting.

## Parameters
* **ped**: Ped id.

## Return value
Whether or not the ped is sprinting. Note that if the ped is sprinting, it will return `1` instead of `true`.
