<!-- # [ARCHIVE] -->

> [!WARNING]
> This has **not been validaded** after the extensive game engine reworks introduced in version 7.0 and above. This project exists as-is.

### Silent's Messy Shader Mod - ReShade Add-on version for FFXIV

Addon port by [4lex4nder](https://github.com/4lex4nder).
Shader resources by [s-ilent](https://github.com/s-ilent/smsm-ff14).

###### "ReShade version of Silent's shader replacements."

#### Notable qualities still present in this version include:

-   Much improved native Debanding (you'll notice there's a lot less color banding in the skybox).
-   Better Colors and Contrast, with the removal of the dreaded yellow-ish tint from the game, presentation is clearer.
-   Filmic tonemmaping.

**You can still use all of your other ReShade shaders and presets, while benefiting from these improvements!**

##### For more information read the description from the original here: https://github.com/s-ilent/smsm-ff14.

### Basic comparison:

_No ReShade shaders, only default and add-on._

#### [Click here for a side-by-side comparison.](https://imgsli.com/MTY2MTcz)

#### Vanilla:

![01-Before](/.assets/01-before.png)

#### Add-on:

![02-After](/.assets/02-after.png)

### Installation/Usage:

1. Download/clone the repository and extract the files.
2. The `ShaderFixes` folder goes to your FFXIV installation inside the `game` folder, alongside the `ffxiv_dx11.exe`.
3. `shader_replace.addon` goes into your Add-on search path directory. <br>
   You can configure that in the Add-ons tab in the in-game ReShade interface, [as shown here](https://i.imgur.com/11rMBDi.png).
4. Enable the `Shader Replace` add-on in the Add-ons tab and restart the game.

#### Notes:

-   Configurations aren't loaded in this version, so there's no point in changing them. At this stage, all the add-on does is load the shaders that are inside the `ShaderFixes` folder directly without customization.
-   Tested with ReShade 6.0.1.
