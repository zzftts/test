# <center> Rep2wav: Noise Robust TTS Using self-supervised pre-trained model </center>
<br>
## Abstract
<div style="text-align: justify"> Benefiting from the development of deep learning, text-to-speech (TTS) technology using clean speech has now achieved significant performance improvements. 
The data collected from real scenes often contain noise and generally need to be denoised by speech enhancement models.	
Noise-robust TTS models are often trained using enhanced speech, which is susceptible to speech distortion and background noise, which can affect the quality of the synthesized speech. 
Meanwhile, the self-supervised pre-trained model exhibits excellent noise robustness on many speech tasks, and we conjecture that the representation has a better ability to tolerate noise perturbations. 
Therefore, we explore methods to improve the noise robustness of TTS models using pre-trained models. 
In this paper, based on the HIFI-GAN model we first propose the representation-to-waveform vocoder, which aims to learn to map the representation of the pre-trained model to the waveform. 
Second, based on the Fastspeech2 model we propose the text-to-representation Fastspeech2 model, which aims to learn to map text to pre-trained model representations. 
Finally, experimental results on the LJSpeech and LibriTTS datasets show that our method outperforms using speech enhancement methods in both subjective and objective metrics.
Audio samples are available	at https://zzftts.github.io/.	
 </div> 

<br>

![arch](images/abc.png)

<br>
