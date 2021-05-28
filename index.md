# <center> DiffSVC: A Diffusion Probabilistic Model for Singing Voice Conversion </center>

<center> Songxiang Liu *, Yuewen Cao *, Dan Su, Helen Meng </center> 

<center> Human-Computer Communications Laboratory, The Chinese University of Hong Kong </center>

<center> Tencent AI Lab </center>

* Equal contribution and work done during internship at Tencent AI Lab.

## Abstract
Singing voice conversion (SVC) is one promising technique which can enrich the way of human-computer interaction by endowing a computer the ability to produce high-fidelity and expressive singing voice.
In this paper, we propose DiffSVC, an SVC system based on denoising diffusion probabilistic model. DiffSVC uses phonetic posteriorgrams (PPGs) as content features. A denoising module is trained in DiffSVC, which takes destroyed mel spectrogram produced by the diffusion/forward process and its corresponding step information as input to predict the added Gaussian noise. We use PPGs, fundamental frequency features and loudness features as auxiliary input to assist the denoising process. Experiments show that DiffSVC can achieve superior conversion performance in terms of naturalness and voice similarity to current state-of-the-art SVC approaches.

## Demo
### Samples from the target female singer.
| 1 | 2 | 3 | 4 | 
| :--- | :--- | :--- | :--- |
| <audio src="wavs/ref/1.wav" controls preload></audio> | <audio src="wavs/ref/2.wav" controls preload></audio> | <audio src="wavs/ref/3.wav" controls preload></audio> | <audio src="wavs/ref/4.wav" controls preload></audio> |
| --- | --- | --- | --- |
