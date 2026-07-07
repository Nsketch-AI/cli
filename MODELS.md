# Nsketch Models

Live catalog: `nsketch models list --json`. Credit pricing: `https://nsketchai.com/api/mobile/pricing`.

## Image Models (39)

| Model ID | Name |
|---|---|
| `img-imagen4-preview` | Imagen4 Preview |
| `img-imagen3` | Imagen3 |
| `img-grok-imagine` | Grok Imagine |
| `img-grok-imagine-edit` | Grok Imagine Edit |
| `img-nano-banana` | Nano Banana |
| `img-nano-banana-edit` | Nano Banana Edit |
| `img-nano-banana-pro` | Nano Banana Pro |
| `img-nano-banana-pro-edit` | Nano Banana Pro Edit |
| `img-nano-banana-2` | Nano Banana 2 |
| `img-nano-banana-2-edit` | Nano Banana 2 Edit |
| `img-nano-banana-2-lite` | Nano Banana 2 Lite |
| `img-nano-banana-2-lite-edit` | Nano Banana 2 Lite Edit |
| `img-seedream-v4` | Seedream V4 |
| `img-seedream-v4-edit` | Seedream V4 Edit |
| `img-seedream-v45` | Seedream V45 |
| `img-seedream-v45-edit` | Seedream V45 Edit |
| `img-seedream-v5-lite` | Seedream V5 Lite |
| `img-seedream-v5-lite-edit` | Seedream V5 Lite Edit |
| `img-flux-kontext-pro` | Flux Kontext Pro |
| `img-gpt-image-1` | Gpt Image 1 |
| `img-gpt-image-1-edit` | Gpt Image 1 Edit |
| `img-gpt-image-1-5` | Gpt Image 1 5 |
| `img-gpt-image-1-5-edit` | Gpt Image 1 5 Edit |
| `img-gpt-image-2` | Gpt Image 2 |
| `img-gpt-image-2-edit` | Gpt Image 2 Edit |
| `img-hunyuan-v21` | Hunyuan V21 |
| `img-hunyuan-v3` | Hunyuan V3 |
| `img-wan-v22-a14b` | Wan V22 A14b |
| `img-wan-v26` | Wan V26 |
| `img-wan-v26-edit` | Wan V26 Edit |
| `img-wan-v27` | Wan V27 |
| `img-wan-v27-edit` | Wan V27 Edit |
| `img-wan-v27-pro` | Wan V27 Pro |
| `img-wan-v27-pro-edit` | Wan V27 Pro Edit |
| `img-reve` | Reve |
| `img-reve-edit` | Reve Edit |
| `img-kling-o1` | Kling O1 Image |
| `img-flux-2-max` | Flux 2 Max |
| `img-flux-2-max-edit` | Flux 2 Max Edit |

## Video Models (49)

| Model ID | Name |
|---|---|
| `vid-grok-imagine-video` | Grok Imagine Video |
| `vid-grok-image-1.5-video` | Grok Image 1 5 Video |
| `vid-kling-v3` | Kling V3 |
| `vid-kling-v3-turbo` | Kling V3 Turbo |
| `vid-kling-2.6-pro` | Kling 2 6 Pro |
| `kling-o1-transition` | Kling O1 Transition |
| `kling-o1` | Kling O1 |
| `kling-o3` | Kling O3 |
| `vid-kling-2.5-pro` | Kling 2 5 Pro |
| `kling-2.5-turbo-transition` | Kling 2 5 Transition |
| `kie-sora-2` | Sora 2 |
| `vid-gemini-omni-video` | Gemini Omni Video |
| `vid-veo-3.1` | Veo 3 1 |
| `veo3.1-transition` | Veo 3 1 Transition |
| `vid-veo-3.1-fast` | Veo 3 1 Fast |
| `veo3.1-fast-transition` | Veo 3 1 Fast Transition |
| `vid-veo-3.1-lite` | Veo 3 1 Lite |
| `veo3.1-lite-transition` | Veo 3 1 Lite Transition |
| `kie-wan-2.6` | Wan 2 6 |
| `kie-wan-2.5` | Wan 2 5 |
| `vid-wan-2.1` | Wan 2 1 |
| `vid-hailuo-2.3-pro` | Hailuo 2 3 Pro |
| `vid-hailuo-2.3` | Hailuo 2 3 |
| `vid-ovi` | Ovi |
| `vid-kandinsky-5` | Kandinsky 5 |
| `vid-seedance-lite` | Seedance Lite |
| `vid-seedance-pro` | Seedance Pro |
| `seedance-pro-transition` | Seedance Pro Transition |
| `kie-seedance-1.5-pro` | Seedance 1 5 Pro |
| `kie-seedance-1.5-pro-transition` | Seedance 1 5 Pro Transition |
| `pastapi-seedance-2-preview` | Seedance 2 Preview |
| `pastapi-seedance-2-fast-preview` | Seedance 2 Fast Preview |
| `pastapi-seedance-2-mini-preview` | Seedance 2 Mini Preview |
| `dreamina-seedance-2-omni` | Seedance 2 Omni |
| `dreamina-seedance-2-omni-fast` | Seedance 2 Omni Fast |
| `dreamina-seedance-2-mini-omni` | Seedance 2 Mini Omni |
| `pixverse-v5` | Pixverse V5 |
| `pixverse-v5-transition` | Pixverse V5 Transition |
| `pixverse-v5.6` | Pixverse V56 |
| `pixverse-v5.6-transition` | Pixverse V56 Transition |
| `pixverse-v6` | Pixverse V6 |
| `pixverse-v6-transition` | Pixverse V6 Transition |
| `vid-hunyuan` | Hunyuan |
| `vid-ltx-2-pro` | Ltx 2 Pro |
| `vid-ltx-2-fast` | Ltx 2 Fast |
| `vid-ltx-2.3-pro` | Ltx 2 3 Pro |
| `vid-ltx-2.3-fast` | Ltx 2 3 Fast |
| `vid-ltx` | Ltx |
| `vid-happy-horse` | Happy Horse |

## Voice Models (2)

| Model ID | Name |
|---|---|
| `voice-clone-v1` | Vibevoice 7b |
| `voice-sonic-3` | Sonic 3 |

## Usage

```bash
nsketch generate image --prompt "..." --model <model-id> --wait
nsketch generate video --prompt "..." --model <model-id> --wait
```

Model ids ending in `-edit` require `--image <pathOrUrl>`.
