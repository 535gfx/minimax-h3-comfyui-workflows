# Links: every model and node pack

Every workflow's loaders carry the same links. Node packs install from ComfyUI's Manager or from the GitHub link. A folder is under `ComfyUI/models/`.

FastH3, Turbo, Pika, Singularity, fused and SeedVR2 at 4K run on ComfyUI's own nodes, so they need no pack.

## 2x upscalers (video 01)

### MiniMax H3 latent upscaler, 2x

Node packs: [MiniMax H3 latent upscaler](https://github.com/LBH-123-AI/Comfyui_Minimax_h3_latent_Upscaler)

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `latent_upscale_models` | [minimax_h3_latent_upscaler_3d_conv_v1_bf16.safetensors](https://huggingface.co/LBH-123-AI/Minimax_h3_latent_Upscaler/resolve/main/minimax_h3_latent_upscaler_3d_conv_v1/minimax_h3_latent_upscaler_3d_conv_v1_bf16.safetensors) | 0.69 GB |  |
| `diffusion_models` | [minimax_h3_fl2va_bf16.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/diffusion_models/minimax_h3_fl2va_bf16.safetensors) | 66.28 GB |  |

### SeedVR2, 2x

Node packs: [ComfyUI-SeedVR2_VideoUpscaler by numz](https://github.com/numz/ComfyUI-SeedVR2_VideoUpscaler)

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `SEEDVR2` | [seedvr2_ema_3b_fp16.safetensors](https://huggingface.co/numz/SeedVR2_comfyUI/resolve/main/seedvr2_ema_3b_fp16.safetensors) | 6.78 GB |  |
| `SEEDVR2` | [seedvr2_ema_7b_fp16.safetensors](https://huggingface.co/numz/SeedVR2_comfyUI/resolve/main/seedvr2_ema_7b_fp16.safetensors) | 16.48 GB |  |
| `SEEDVR2` | [ema_vae_fp16.safetensors](https://huggingface.co/numz/SeedVR2_comfyUI/resolve/main/ema_vae_fp16.safetensors) | 0.50 GB |  |

## 4K upscalers

### FlashVSR 1.1

Node packs: [FlashVSR Stock](https://github.com/Pizzawookiee/ComfyUI-FlashVSR-Stock)

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `flashvsr` | [FlashVSR1_1-int8_convrot.safetensors](https://huggingface.co/pizzawookiee/FlashVSR-1.1/resolve/main/FlashVSR1_1-int8_convrot.safetensors) | 1.45 GB |  |
| `flashvsr` | [LQ_proj_in.safetensors](https://huggingface.co/pizzawookiee/FlashVSR-1.1/resolve/main/LQ_proj_in.safetensors) | 0.58 GB |  |
| `flashvsr` | [Prompt.safetensors](https://huggingface.co/pizzawookiee/FlashVSR-1.1/resolve/main/Prompt.safetensors) | 0.00 GB |  |
| `vae` | [Wan2.1_VAE.pth](https://huggingface.co/JunhaoZhuang/FlashVSR-v1.1/resolve/main/Wan2.1_VAE.pth) | 0.51 GB | the makers' file |

### MiniMax H3 latent upscaler

Node packs: [MiniMax H3 latent upscaler](https://github.com/LBH-123-AI/Comfyui_Minimax_h3_latent_Upscaler)

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `latent_upscale_models` | [minimax_h3_latent_upscaler_3d_conv_v1_bf16.safetensors](https://huggingface.co/LBH-123-AI/Minimax_h3_latent_Upscaler/resolve/main/minimax_h3_latent_upscaler_3d_conv_v1/minimax_h3_latent_upscaler_3d_conv_v1_bf16.safetensors) | 0.69 GB |  |

### SeedVR2 3B (one piece + join)

Node packs: [KJNodes, join only](https://github.com/kijai/ComfyUI-KJNodes)

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [seedvr2_3b_int8_convrot.safetensors](https://huggingface.co/Comfy-Org/SeedVR2/resolve/main/diffusion_models/seedvr2_3b_int8_convrot.safetensors) | 3.46 GB |  |
| `vae` | [seedvr2_ema_vae_fp16.safetensors](https://huggingface.co/Comfy-Org/SeedVR2/resolve/main/vae/seedvr2_ema_vae_fp16.safetensors) | 0.50 GB |  |

### LTX-2.5 Refine Details

Node packs: [LTXVideo by Lightricks](https://github.com/Lightricks/ComfyUI-LTXVideo)

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [ltx-2.5-22b-distilled-transformer-comfy-int8-convrot.safetensors](https://huggingface.co/Lightricks/LTX-2.5/resolve/main/diffusion_models/ltx-2.5-22b-distilled-transformer-comfy-int8-convrot.safetensors) | 21.50 GB | press Agree and Access on the repo page first |
| `text_encoders` | [gemma4-12b-with-proj-ltx-2.5-comfy-int8-convrot.safetensors](https://huggingface.co/Lightricks/LTX-2.5/resolve/main/text_encoders/gemma4-12b-with-proj-ltx-2.5-comfy-int8-convrot.safetensors) | 15.37 GB | press Agree and Access on the repo page first |
| `vae` | [ltx-2.5-video-vae-bf16.safetensors](https://huggingface.co/Lightricks/LTX-2.5/resolve/main/vae/ltx-2.5-video-vae-bf16.safetensors) | 1.47 GB | press Agree and Access on the repo page first |
| `loras` | [ltx-2.5-22b-ic-lora-refine-details-1.0.safetensors](https://huggingface.co/Lightricks/LTX-2.5-22b-IC-LoRA-Refine-Details/resolve/main/ltx-2.5-22b-ic-lora-refine-details-1.0.safetensors) | 1.31 GB | press Agree and Access on the repo page first |

## MiniMax H3

### Shared by all H3 workflows

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `text_encoders` | [qwen3vl_32b_minimax_h3_bf16.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/text_encoders/qwen3vl_32b_minimax_h3_bf16.safetensors) | 51.51 GB |  |
| `text_encoders` | [qwen3vl_32b_minimax_h3_nvfp4_awq.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/text_encoders/qwen3vl_32b_minimax_h3_nvfp4_awq.safetensors) | 15.69 GB | the smaller option; the videos ran the bf16 one |
| `vae` | [minimax_h3_video_vae_int8_convrot.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/vae/minimax_h3_video_vae_int8_convrot.safetensors) | 2.81 GB |  |
| `vae` | [minimax_h3_video_vae_fp16.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/vae/minimax_h3_video_vae_fp16.safetensors) | 5.21 GB | the latent upscaler workflows |
| `vae` | [minimax_h3_audio_vae_fp32.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/vae/minimax_h3_audio_vae_fp32.safetensors) | 0.61 GB |  |

### Full model

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [minimax_h3_ref2va_bf16.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/diffusion_models/minimax_h3_ref2va_bf16.safetensors) | 66.28 GB |  |
| `diffusion_models` | [minimax_h3_fl2va_bf16.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/diffusion_models/minimax_h3_fl2va_bf16.safetensors) | 66.28 GB |  |

### Pruned

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [minimax_h3_ref2va_pruned_int8_convrot.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/diffusion_models/minimax_h3_ref2va_pruned_int8_convrot.safetensors) | 20.97 GB |  |
| `diffusion_models` | [minimax_h3_ref2va_pruned_bf16.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/diffusion_models/minimax_h3_ref2va_pruned_bf16.safetensors) | 40.23 GB |  |
| `diffusion_models` | [minimax_h3_fl2va_pruned_int8_convrot.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/diffusion_models/minimax_h3_fl2va_pruned_int8_convrot.safetensors) | 20.97 GB |  |
| `diffusion_models` | [minimax_h3_fl2va_pruned_bf16.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/diffusion_models/minimax_h3_fl2va_pruned_bf16.safetensors) | 40.23 GB |  |

### FastH3 v1

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [minimax_h3_fastvideo_vsa_datafree_1300step_4step_int8_convrot.safetensors](https://huggingface.co/Kijai/MiniMax-H3-experimental/resolve/main/minimax_h3_fastvideo_vsa_datafree_1300step_4step_int8_convrot.safetensors) | 22.90 GB |  |

### FastH3 V2

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [fastvideo_fasth3_8step_v2_pruned_int8_convrot.safetensors](https://huggingface.co/FastVideo/FastVideo-FastH3-Comfy/resolve/main/diffusion_models/fastvideo_fasth3_8step_v2_pruned_int8_convrot.safetensors) | 22.13 GB |  |

### FastH3 Trim

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [fastvideo_fasth3_trim_8step_int8_convrot.safetensors](https://huggingface.co/FastVideo/FastVideo-FastH3-Trim-Comfy/resolve/main/diffusion_models/fastvideo_fasth3_trim_8step_int8_convrot.safetensors) | 18.92 GB |  |

### TaoMate 3-step

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `loras` | [taomate_h3_3step_comfy.safetensors](https://huggingface.co/Robert1212star/TaoMate-H3-3Step-ComfyUI/resolve/main/taomate_h3_3step_comfy.safetensors) | 2.48 GB |  |

### DMAD 4-step

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `loras` | [dmad_minimax_h3_4step_full_critic_comfyui.safetensors](https://huggingface.co/ZhengmingYu/DMAD/resolve/main/minimax_h3/dmad_minimax_h3_4step_full_critic_comfyui.safetensors) | 1.96 GB |  |

### FastH3 Omni

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [fasth3_omniref_8step_pruned_int8_convrot.safetensors](https://huggingface.co/FastVideo/FastH3-OmniRef-Comfy/resolve/main/diffusion_models/fasth3_omniref_8step_pruned_int8_convrot.safetensors) | 22.21 GB |  |

### Turbo

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `loras` | [minimax_h3_ref2v_turbo_4step_v0.1_comfyui_bf16.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/loras/minimax_h3_ref2v_turbo_4step_v0.1_comfyui_bf16.safetensors) | 1.96 GB |  |
| `loras` | [minimax_h3_ref2v_turbo_4step_v1.0_768p_comfyui_bf16.safetensors](https://huggingface.co/lightx2v/Minimax-h3-Turbo/resolve/main/minimax_h3_ref2v_turbo_4step_v1.0_768p_comfyui_bf16.safetensors) | 1.96 GB |  |
| `loras` | [minimax_h3_ref2v_turbo_8step_v1.0_768p_comfyui_bf16.safetensors](https://huggingface.co/lightx2v/Minimax-h3-Turbo/resolve/main/minimax_h3_ref2v_turbo_8step_v1.0_768p_comfyui_bf16.safetensors) | 1.96 GB |  |
| `loras` | [minimax_h3_ref2v_turbo_8step_v1.1_768p_comfyui_bf16.safetensors](https://huggingface.co/lightx2v/Minimax-h3-Turbo/resolve/main/minimax_h3_ref2v_turbo_8step_v1.1_768p_comfyui_bf16.safetensors) | 1.96 GB |  |
| `loras` | [minimax_h3_fl2v_turbo_4step_v1.2_768p_comfyui_bf16.safetensors](https://huggingface.co/lightx2v/Minimax-h3-Turbo/resolve/main/minimax_h3_fl2v_turbo_4step_v1.2_768p_comfyui_bf16.safetensors) | 1.96 GB |  |
| `loras` | [minimax_h3_fl2v_turbo_4step_v1.3_768p_comfyui_bf16.safetensors](https://huggingface.co/lightx2v/Minimax-h3-Turbo/resolve/main/minimax_h3_fl2v_turbo_4step_v1.3_768p_comfyui_bf16.safetensors) | 1.96 GB |  |
| `loras` | [minimax_h3_fl2v_turbo_8step_v1.0_768p_comfyui_bf16.safetensors](https://huggingface.co/lightx2v/Minimax-h3-Turbo/resolve/main/minimax_h3_fl2v_turbo_8step_v1.0_768p_comfyui_bf16.safetensors) | 1.96 GB |  |
| `loras` | [minimax_h3_fl2v_turbo_8step_v1.1_768p_comfyui_bf16.safetensors](https://huggingface.co/lightx2v/Minimax-h3-Turbo/resolve/main/minimax_h3_fl2v_turbo_8step_v1.1_768p_comfyui_bf16.safetensors) | 1.96 GB |  |

### Pika H3 Flex

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `loras` | [pika_h3_flex_ref2va_v1_bf16.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/loras/pika_h3_flex_ref2va_v1_bf16.safetensors) | 1.96 GB |  |
| `loras` | [pika_h3_flex_fl2va_v1_bf16.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/loras/pika_h3_flex_fl2va_v1_bf16.safetensors) | 1.96 GB |  |

### Pika Flex Turbo

akhaliq's merge of the Pika H3 Flex adapter with a speed LoRA, hosted by Pika Labs.

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `loras` | [pika_h3_flex_turbo_2step_draft_ref2va.safetensors](https://huggingface.co/Pika-Labs/Pika-H3-Flex-Turbo-LoRA/resolve/main/pika_h3_flex_turbo_2step_draft_ref2va.safetensors) | 3.91 GB |  |
| `loras` | [pika_h3_flex_turbo_4step_ref2va.safetensors](https://huggingface.co/Pika-Labs/Pika-H3-Flex-Turbo-LoRA/resolve/main/pika_h3_flex_turbo_4step_ref2va.safetensors) | 3.91 GB |  |
| `loras` | [pika_h3_flex_turbo_8step_hd_ref2va.safetensors](https://huggingface.co/Pika-Labs/Pika-H3-Flex-Turbo-LoRA/resolve/main/pika_h3_flex_turbo_8step_hd_ref2va.safetensors) | 3.91 GB |  |
| `loras` | [pika_h3_flex_turbo_4step_fl2va.safetensors](https://huggingface.co/Pika-Labs/Pika-H3-Flex-Turbo-LoRA/resolve/main/pika_h3_flex_turbo_4step_fl2va.safetensors) | 3.91 GB |  |
| `loras` | [pika_h3_flex_turbo_8step_hd_fl2va.safetensors](https://huggingface.co/Pika-Labs/Pika-H3-Flex-Turbo-LoRA/resolve/main/pika_h3_flex_turbo_8step_hd_fl2va.safetensors) | 3.91 GB |  |

### VDN-H3, makers' recipe and Saganaki22's node

Node packs: [ComfyUI-VDN-H3 by Saganaki22](https://github.com/Saganaki22/ComfyUI-VDN-H3)

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [minimax_h3_fl2va_int8_convrot.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/diffusion_models/minimax_h3_fl2va_int8_convrot.safetensors) | 34.04 GB |  |
| `diffusion_models` | [minimax_h3_ref2va_int8_convrot.safetensors](https://huggingface.co/Comfy-Org/MiniMax-H3/resolve/main/diffusion_models/minimax_h3_ref2va_int8_convrot.safetensors) | 34.04 GB |  |
| `vdn/stage-dmd-step-250` | [stage-dmd-step-250/adapters/default/adapter_model.safetensors](https://huggingface.co/OpenVDN/vdn-minimax-h3/resolve/main/stage-dmd-step-250/adapters/default/adapter_model.safetensors) | 0.33 GB |  |
| `vdn/stage-dmd-step-250` | [stage-dmd-step-250/adapters/turbo/adapter_model.safetensors](https://huggingface.co/OpenVDN/vdn-minimax-h3/resolve/main/stage-dmd-step-250/adapters/turbo/adapter_model.safetensors) | 0.85 GB |  |
| `vdn/stage-dmd-step-250` | [stage-dmd-step-250/linear_branch/model.safetensors](https://huggingface.co/OpenVDN/vdn-minimax-h3/resolve/main/stage-dmd-step-250/linear_branch/model.safetensors) | 4.28 GB |  |

### PDD 8-step

Node packs: [MiniMax H3 PDD Acc](https://github.com/Jalen-Brunson/ComfyUI-MiniMax-H3-PDD-Acc)

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `pdd_acc` | [MiniMax-H3-Ref2VA-Acc-8Step.safetensors](https://huggingface.co/alibaba-pai/MiniMax-H3-Acc-LoRAs/resolve/main/MiniMax-H3-Ref2VA-Acc-8Step.safetensors) | 1.37 GB |  |
| `pdd_acc` | [MiniMax-H3-FL2VA-Acc-8Step.safetensors](https://huggingface.co/alibaba-pai/MiniMax-H3-Acc-LoRAs/resolve/main/MiniMax-H3-FL2VA-Acc-8Step.safetensors) | 1.37 GB |  |

### Singularity

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [Minimax-h3_Singularity_ref2va_Pruned_v1.3_int8.safetensors](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity/resolve/main/Minimax-h3_Singularity_ref2va_Pruned_v1.3_int8.safetensors) | 20.97 GB |  |
| `diffusion_models` | [Minimax-h3_Singularity_ref2va_v2_pruned_int8.safetensors](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity/resolve/main/Minimax-h3_Singularity_ref2va_v2_pruned_int8.safetensors) | 20.97 GB |  |

### Fused

| folder under `ComfyUI/models/` | file | size | note |
|---|---|---|---|
| `diffusion_models` | [minimax_h3_fused_refdelta_r1024_turbo8_mystic07_int8_convrot.safetensors](https://huggingface.co/MATLOWAI/minimax-h3-fused-turbo-int8-convrot/resolve/main/diffusion_models/minimax_h3_fused_refdelta_r1024_turbo8_mystic07_int8_convrot.safetensors) | 20.98 GB |  |
