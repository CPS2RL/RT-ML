# Machine Learning
Machine learning is a field of artificial intelligence that has granted computers the capability to learn from data (experience). This data can be from sensor measurements (e.g., light and temperature readings) to health records. The primary goal of machine learning is to build robust models through model training to make predictions and decisions about said data reliably. Weather forecasting systems, recommendation systems, automatic speech recognition, and facial recognition systems are examples of machine learning.

Machine learning algorithms are often incompatible with temporal constraints. Because of this, machine learning techniques are often at the application level. So then, the goal is to figure out ways to make complex, and machine learning applications work on embedded systems that are power, processing, memory (RAM/Cache) constrained devices.

## Speech recognition
To demonstrate machine learning, the goal was to build a speech recognition system that could be used to voice-control an industrial robot. To do this, one would need to develop a speech/word(s) model via audio training in something like TensorFlow, Keras, PyTorch, etc. Unfortunately, this part of the project never materialized. Still, the process is most clearly outlined in the [Digi-Key TensorFlow Lite series](https://www.youtube.com/watch?v=0fn7pj7Dutc&t=0s&ab_channel=Digi-Key). Furthermore, there are several end-to-end speech recognition services and platforms that are detailed by the people from seeedstudio [here](https://www.seeedstudio.com/blog/2020/01/23/offline-speech-recognition-on-raspberry-pi-4-with-respeaker/).

### ReSpeaker
A microphone will be needed independent of what machine learning platform or speech recognition library one uses. Therefore, the ReSpeaker Mic Array v2.0 was chosen as it is a capable far-field microphone is a hardware-based solution for creating or adding voice-interface to projects. All of the documentation and code examples can be found on the [ReSpeaker Mic Array v2.0 wiki](https://wiki.seeedstudio.com/ReSpeaker_Mic_Array_v2.0/).

<img src="ReSpeaker-gif.gif" alt="ReSepaker" style="zoom:60%;" />

