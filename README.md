# Modelos do Separador de Faixas

Arquivos ONNX usados pelas funções do site (baixados na primeira execução de cada servidor).
Pesos guardados em float16; o código converte para float32 ao carregar.

- `htdemucs_6s.f16.onnx` — Demucs v4 6 fontes (Meta, licença MIT): https://github.com/facebookresearch/demucs
- `cnn14.f16.onnx` — PANNs CNN14, classificador AudioSet (licença MIT): https://github.com/qiuqiangkong/audioset_tagging_cnn
