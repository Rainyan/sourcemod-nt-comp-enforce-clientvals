# sourcemod-nt-comp-enforce-clientvals
SourceMod plugin for competitive Neotokyo.

This plugin enforces certain client cvars for competitive play, as described <a href="#list-of-enforced-values-and-reasons">in more detail below</a>.

## List of enforced values, and reasons

### r_shadowrendertotexture

#### Default value (1)

This is how the shadow should look like, with its angle tied to the map's sun angle, such that the player can predict when they're exposing their shadow based on map knowledge.

![r_shadowrendertotexture_1](https://user-images.githubusercontent.com/6595066/210471044-3a06dcb8-4e39-4eec-bd66-2766e1e25dc6.jpg)

#### Modified values

Custom values will render an always front-facing, blob-shaped shadow, which can reveal enemies behind corners in ways that normally aren't possible.

![r_shadowrendertotexture_0](https://user-images.githubusercontent.com/6595066/210471026-9ea1f4af-51c0-4e54-931e-7edbcde7f4f2.jpg)  

### v_vmtweak

#### Default value (0)  

Weapon viewmodel will be visible as normal.  

#### Modified values  

Custom values (1) can allow clients to make the viewmodel invisible or otherwise look different to normal, potentially providing a gameplay advantage.  

## Building

### Requirements

* SourceMod 1.7 or newer
