# Wan 3.0 Prompt: Rose Reveal (consistent AI influencer)

The exact prompt behind the rose-reveal clip from the MatrixLab Instagram reel.
One character, three references, one 10-second shot.

## Settings

| Setting | Value |
|---|---|
| Model | Wan 3.0 |
| Mode | Generate (reference-to-video), no start image |
| Aspect ratio | 16:9 |
| Duration | 10 s |

## Inputs you need

1. **Image 1 - opening scene (16:9):** your character in the room, outfit and starting pose you want the video to begin with.
2. **Image 2 - face reference:** a clean, sharp face image of your character (a character sheet view works well).
3. **Video 1 - motion reference:** a short clip that shows the movement you want. It only drives action and timing, not the framing.

Replace "Lina" with your character's name and adjust outfit, room and bouquet details to match your Image 1.

## Prompt

```text
A continuous 10-second horizontal 16:9 video of ONE woman, Lina. All three references show this same woman.

Image 1 defines the opening scene: the wide landscape framing, the room with pale horizontal window blinds, the daylight, her red sparkling dress, jewelry and manicure, and her starting pose slightly right of center, holding the black-wrapped bouquet beside her face on screen-left. Begin the video matching Image 1 as closely as possible.

Image 2 defines her identity: Lina's face, facial anatomy, light blonde hair, freckles, skin tone and body proportions. Keep her identical in every frame, including head turns, closed eyes, puckered lips, smiles and partial occlusion by the bouquet.

Video 1 defines only the action sequence and timing. Follow its choreography, but do not copy its vertical framing, crop or camera distance. Stay in the wide 16:9 view of Image 1, with the window blinds visible on both sides.

ACTION
0-2.5s: She holds the bouquet's black-paper backside toward the camera beside her face on screen-left, looks up, then lowers her gaze to the lens with small blinks and a pleased smile.
2.5-4s: She rotates the same bouquet across her chest toward screen-right, revealing the dense red roses that were already inside. The black paper briefly passes in front of her face with natural motion blur.
4-6.5s: She cradles the roses across her chest, smiles at the lens, briefly closes her eyes and looks down at the flowers, then back to the lens.
6.5-8.5s: She brings the bouquet forward toward the camera so the roses fill the lower foreground, her face visible above them, and makes a playful kiss pose with narrowed eyes.
8.5-10s: She relaxes into a warm closed-mouth smile and lowers the bouquet toward screen-left, still holding it, ending on a short living hold.

CONTINUITY
Same red sparkling dress, necklaces, bracelets, long dark red manicure, black wrapping, green base in clear film and red satin ribbons throughout. One woman, one bouquet, both hands physically attached to it. Nearly stationary smartphone camera with tiny natural drift; the closer view comes from her and the bouquet approaching, not from zoom. Same blinds, window frame and constant daylight.

AUDIO
Quiet indoor room tone with soft paper rustles during grip changes and the rotation. No speech, music, singing or kiss sound.

AVOID
No vertical framing, letterboxing, crop to portrait, captions, text, logos, watermark, second person, duplicate face, extra bouquet, roses growing from the green base, unwrapping, changing clothes or jewelry, face morphing, identity drift, extra fingers, fused hands, dropped bouquet, zoom, camera cuts or transitions.
```

## Why it works

- **Each reference has one job.** Scene, identity and motion are separated, so the model does not mix them up.
- **Timed action beats** keep the 10 seconds smooth instead of random.
- **CONTINUITY and AVOID** lock outfit, props and hands, the usual failure points.

---

Want the full workflow to build a consistent character and dataset first?
Follow [@matrixlabai](https://www.instagram.com/matrixlabai/) and check out MatrixLab.
