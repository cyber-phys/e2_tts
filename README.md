# Implementation of [E2 TTS: Embarrassingly Easy Fully Non-Autoregressive Zero-Shot TTS](https://arxiv.org/abs/2406.18009)

## Getting started - Inference
1. install [just](https://just.systems)
2. download the compressed rfwave [vocoder ckpt trained with LibriTTS](https://drive.google.com/file/d/1IQNXAAVRTtr9P8Gc-CoPeRIJ_l_O4y38).
3. download the compressed acoustic [e2 tts ckpt trained with LJSpeech](https://drive.google.com/file/d/1NjaxSuCQSDBy2gys9cRcbpvQcRW-szNs/view?usp=sharing)
4. run `just play`

## Training
`python3 train.py -c config/e2_tts.yaml`

## Examples
Synthesized samples from this checkpoint can be found [here](https://drive.google.com/file/d/1EpNC_7LqE9-52U7sn1ohchWaQn54sAvr/view?usp=sharing)

Some discussion can be found [here](https://github.com/lucidrains/e2-tts-pytorch/issues/25).
