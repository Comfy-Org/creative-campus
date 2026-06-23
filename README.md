# Creative Campus — Case Study Workflows

Companion ComfyUI workflows from [Comfy Education Initiative](https://comfy.org/education) case studies. These are the actual graphs the featured artists used, shared so others can open, study, and build on them.

## Xindi Zhang — *The Song of Drifters*

USC MFA Expanded Animation thesis. Student Academy Award (Gold, 2025) and 98th Academy Awards shortlist, built in ComfyUI. The pipeline restyles the artist's own iPhone live-action and Blender 3D using style transfer in SD 1.5 (IP-Adapter + ControlNet), with custom LoRAs trained on her own city footage.

| File | What it does |
|------|--------------|
| [`xindi-zhang/Drifters_styleTransfer.json`](xindi-zhang/Drifters_styleTransfer.json) | Style-transfer graph: restyles source footage with the artist's own illustrations as the style guide |
| [`xindi-zhang/Drifters_stylizedMorphing.json`](xindi-zhang/Drifters_stylizedMorphing.json) | AI morphing graph: blends animated 3D with AI morphing for the dream sequences |

**How to use:** download the `.json`, then in ComfyUI use **Open** (or drag the file onto the canvas) to load the graph. Check the required custom nodes and models before running.

**Credit:** Workflows by Xindi Zhang ([xindizhangart.com](http://xindizhangart.com)). Film: [*The Song of Drifters*](https://vimeo.com/1131160045). Shared with the artist's permission.

The Comfy Education Initiative is coming soon! Register your interest here (https://forms.gle/fVXA8oMeKexHS49CA) to get early access to educational discounts, education exclusive slack / discord communities, and be notified as soon as the program is released.
