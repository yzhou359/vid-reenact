# Audio-driven Neural Gesture Reenactment with Video Motion Graphs

This repository contains a PyTorch implementation of the following paper:

> **Audio-driven Neural Gesture Reenactment with Video Motion Graphs**
>
> [Yang Zhou](https://people.umass.edu/~yangzhou), Jimei Yang, Dingzeyu Li, Jun Saito, Deepali Aneja, [Evangelos Kalogerakis](https://people.cs.umass.edu/~kalo/)
>
> CVPR 2022
>
> **Abstract** Human speech is often accompanied by body gestures including arm and  hand gestures. We present a method that reenacts a high-quality video with gestures matching a target speech audio. The key idea of our method is to split and re-assemble clips from a reference video through a novel video motion graph encoding valid transitions between clips. To seamlessly connect different clips in the reenactment, we propose a pose-aware video blending network which synthesizes video frames around the stitched frames between two clips. Moreover, we developed an audio-based gesture searching algorithm to find the optimal order of the reenacted frames. Our system generates reenactments that are consistent with both the audio rhythms and the speech content. We evaluate our synthesized video quality  quantitatively,  qualitatively, and with user studies, demonstrating that our method produces videos of much higher quality and consistency with the target audio compared to previous work and baselines.
