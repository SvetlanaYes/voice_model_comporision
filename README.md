﻿# voice_model_comporision
 
 model_1: stt_en_quartznet15x5
 
 model_2: stt_en_fastconformer_ctc_large
 
The stt_en_fastconformer_ctc_large model and the stt_en_quartznet15x5 model are both utilized for Automatic Speech Recognition (ASR) tasks, yet they employ distinct architectures and characteristics. **stt_en_fastconformer_ctc_large** relies on the **Transformer-based FastConformer architecture**, offering robust contextual understanding and capturing long-range dependencies in speech signals, making it suitable for tasks requiring intricate language structures. In contrast, **stt_en_quartznet15x5** employs the lightweight QuartzNet architecture, which has **CNN-based architecture**, prioritizing efficiency and speed while maintaining considerable accuracy, making it well-suited for real-time applications or scenarios with resource constraints. The choice between the two models depends on the specific requirements of the ASR task, considering factors such as computational resources, robustness to noise, and the need for contextual understanding.

As the stt_en_fastconformer_ctc_large model employs a Transformer-based architecture, it excels in capturing long-range dependencies. This characteristic is evident in the comparison where it outperforms the CNN-based stt_en_quartznet15x5 model on audio files longer than 15 seconds, as depicted in the accompanying video, where WER for fastconformer transcriptions are mostly low.

[video] https://drive.google.com/file/d/1Q08v6Ss_QQl3xX6VA28RVvjx6fJ0qtRP/view?usp=drive_link

