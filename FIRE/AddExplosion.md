---
ns: FIRE
---
## ADD_EXPLOSION

```c
// 0xE3AD2BDBAEE269AC 0x10AF5258
void ADD_EXPLOSION(float x, float y, float z, int explosionType, float damageScale, BOOL isAudible, BOOL isInvisible, float cameraShake);
```

```
NativeDB Added Parameter 9: BOOL noDamage
```

```
BOOL isAudible = If explosion makes a sound.  
BOOL isInvisible = If the explosion is invisible or not.
BOOL noDamage = false: damage || nodamage = true: no damage
```

```c
enum eExplosionTag
{
	FIREWORK = 38,
	
};
```

## Parameters
* **x**: 
* **y**: 
* **z**: 
* **explosionType**: 
* **damageScale**: 
* **isAudible**: 
* **isInvisible**: 
* **cameraShake**: 

