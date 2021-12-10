# Speech Recognition

In this project, I built a deep neural network that functions as part of an end-to-end automatic speech recognition (ASR) pipeline.
The completed pipeline accepts raw audio as input and returns a predicted transcription of the spoken language.

1. STEP 1 is a pre-processing step that converts raw audio to one of two feature representations that are commonly used for ASR.

2. STEP 2 is an acoustic model which accepts audio features as input and returns a probability distribution over all potential transcriptions.

3. STEP 3 in the pipeline takes the output from the acoustic model and returns a predicted transcription.
