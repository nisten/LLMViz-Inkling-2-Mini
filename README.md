# LLMViz-Inkling-2-Mini
An educational 3D visualization of the Inkling 2 Mini model, drawn as a particle accelerator.

This interactively shows the architecture inside https://huggingface.co/thinkingmachines/Inkling-2-Mini

Live page of it here: https://nisten.github.io/LLMViz-Inkling-2-Mini/

It is all done as a single static index.html, no tools required. You can just download the index.html and open it directly in your browser, it works offline.

The volume of every solid block is proportional to its size in bytes in the published checkpoint (NVFP4 experts in layers 0–19, MXFP8 experts in 20–23, everything else BF16), including quantization scales. One timeline plays a token's inference pass, then the training pass back through the same machine. The 12 looped layers form a ring the token laps 3 times. Hover or tap anything for an explanation.

Let me know of any inaccuracies or hallucinations present <3

Intended for educational purposes but feel free to use it however you want.

Cheers,

Nisten

License: Apache 2.0
