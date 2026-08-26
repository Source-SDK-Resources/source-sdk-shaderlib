# Source 2013 shaderlib

This repo contains the **shaderlib** code for Source 2013, based on the [Orange Box SDK](https://github.com/Source-SDK-Archives/source-sdk-orangebox/tree/master/materialsystem/shaderlib), with minor compatibility fixes.

## Integrating
Add the following to **vpc_scripts/projects.vgc**:
```
$Project "shaderlib"
{
	"materialsystem\shaderlib\shaderlib.vpc"
}
```
Then, in **vpc_scripts/groups.vgc**, add `"shaderlib"` to the group of your choice.
