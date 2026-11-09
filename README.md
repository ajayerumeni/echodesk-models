# EchoDesk speech model

A pinned copy of the speech-recognition model used by EchoDesk, so installs
always get the exact version that was tested.

- **Model:** NVIDIA Parakeet TDT 0.6B v3, int8, exported for sherpa-onnx
- **Weights:** NVIDIA — https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3
- **Export:** the sherpa-onnx project (k2-fsa) —
  https://huggingface.co/csukuangfj/sherpa-onnx-nemo-parakeet-tdt-0.6b-v3-int8
  at revision `2bda32ec70b097a55adaa07d9a7173915b43cc78` (2025-08-16)
- **License:** CC-BY-4.0 (https://creativecommons.org/licenses/by/4.0/)

The four files in the release archive are byte-identical to that revision:

| File | SHA-256 |
|---|---|
| encoder.int8.onnx | acfc2b4456377e15d04f0243af540b7fe7c992f8d898d751cf134c3a55fd2247 |
| decoder.int8.onnx | 179e50c43d1a9de79c8a24149a2f9bac6eb5981823f2a2ed88d655b24248db4e |
| joiner.int8.onnx | 3164c13fc2821009440d20fcb5fdc78bff28b4db2f8d0f0b329101719c0948b3 |
| tokens.txt | d58544679ea4bc6ac563d1f545eb7d474bd6cfa467f0a6e2c1dc1c7d37e3c35d |

Archive `sherpa-onnx-nemo-parakeet-tdt-0.6b-v3-int8.tar.bz2`:
486660067 bytes, SHA-256 `4546ce369c30ca4cdb39d93a5eb8d746106a3b684489d259ed3655398d54422e`.
