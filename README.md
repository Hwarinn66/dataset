# RVC Voice Dataset

Repository for preparing and training an RVC voice-conversion model.

## Dataset status

Current source audio prepared in this ChatGPT session totals about 23 minutes. The source files are being normalized to mono audio for training.

## Intended pipeline

1. Clean and segment source audio
2. Convert to mono / normalize sample rate
3. Extract F0/features (RMVPE)
4. Train RVC model
5. Train feature index
6. Export `.pth` + `.index` for VCClient/w-okada

> Use only voice data you have permission to model.
