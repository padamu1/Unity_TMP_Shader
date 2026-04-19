# Unity_TMP_Shader

Unity TMPro / UI Image SDF Shader Samples

## Folder structure
- `TMP_Shaders/` — Custom SDF shaders for TextMeshPro (original versions)
- `Shaders/` — SDF shaders for UI Image with no TextMeshPro dependency (new)

## TMP_Shaders/TMP_SDF-Mobile_Custom.shader
- Outline1 & Outline2 share the same Color and width
- Text color 2 is determined by multiplying text color 1
- The position of the underlay is affected by the face2 offset

<img width="520" alt="image" src="https://user-images.githubusercontent.com/26586104/184572808-fb7ff2f7-625e-4eeb-9c89-41f21b6844a0.png">

## Shaders/ (non-TMP)
Drop-in SDF shaders for projects that render SDF sprites through UI Image without using TextMeshPro.
- `SDF-Mobile_Custom.shader` — Face/Face2/Outline/Underlay in a single pass
- `SDF-Mobile_ExternalOutline.shader` — Two-pass variant that draws the outline behind the face

### Unity TMPro Shader with hlsl language


-Reference 
</br>
 : https://forum.unity.com/threads/tmpro-draw-external-outline-before-faces.503999/
