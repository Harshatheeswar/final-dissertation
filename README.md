The BabyLM Challenge aims to advance language models using developmentally appropriate datasets, which mir-
ror the learning environments experienced by young children. In this study, we explored the impact of architectural
customization and attention mechanism enhancements on the BabyLlama model, specifically for this challenge.
Our approach included adapting the model to incorporate a selected subset of the OpenSubtitles dataset compris-
ing 20% of the total dataset and enriched with child centric dialogue to better mimic the conversational dynamics
essential for natural language acquisition. We focused on rigorously experimenting with and analyzing the effects
of locally biased attention, a recent innovation in transformers, within the BabyLM’s comprehensive evaluation
framework. This allowed us to deeply understand the interplay between model modifications and performance,
aligning our findings with the established parameters of GPT-2.

Data: Open_Subtitles can be found here https://osf.io/ad7qg/files/osfstorage
1. Make sure  to install all dependencies present in ipynb
2. Carefully clone evaluation pipeline into the same directory as the ipynb
4. Carefully add evaluation data to the evaluation pipeline 
4 ewok data needs permission to access and can be accessed with this link https://huggingface.co/datasets/ewok-core/ewok-core-1.0
5. Navigate to evaluation section
6. Please utilize the GPU if it's available, as each evaluation requires a significant amount of time to complete.
