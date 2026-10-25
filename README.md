# rawdenoise-nind onnx

This repository hosts the RawNIND Bayer ONNX model optimized for Lightcraft's AI Denoise feature.

Due to file size limits, the model files are uploaded as split volumes.

## contents

-  model_bayer.onnx
-  model.json

## model contract
-  input `float32 [1, 4, 512, 512]` (RGGB bayer planes)
-  output `float32 [1, 3, 1024, 1024]` (camera RGB)

## license

The model weights are licensed under GPL-3.0 (derived from the RawNIND project).

Original source: [AyedaOk/rawlab-models.](https://huggingface.co/AyedaOk/rawlab-models)
