# sourcemod-nt-comp-enforce-clientvals
SourceMod plugin for competitive Neotokyo.

This plugin enforces certain client cvars for competitive play, as described in more detail below.

Clients whose cvars violate these rules are kicked from the server, because they must be manually changed by the player. All of the rules enforce default Neotokyo values, so anyone who gets kicked should (hopefully) also have the knowledge on how to revert these changes they've made.

## List of enforced values, and reasons

### r_shadowrendertotexture

#### Default value (1)

This is how the shadow should look like, with its angle tied to the map's sun angle, such that the player can predict when they're exposing their shadow based on map knowledge.

![r_shadowrendertotexture_1](https://user-images.githubusercontent.com/6595066/210471044-3a06dcb8-4e39-4eec-bd66-2766e1e25dc6.jpg)

#### Modified values

Custom values will render an always front-facing, blob-shaped shadow, which can reveal enemies behind corners in ways that normally aren't possible.

![r_shadowrendertotexture_0](https://user-images.githubusercontent.com/6595066/210471026-9ea1f4af-51c0-4e54-931e-7edbcde7f4f2.jpg)
