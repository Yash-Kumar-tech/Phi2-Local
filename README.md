# Running Phi-2 Locally
This is a project to run Microsoft's Ph-2 model locally on your system. Phi-2 is a transformer based 2.7 billion parameter model that has been trained on data source consisting of various NLP synthetic texts and filtered websites. Although it is far from having the highest number of parameters, it showcases a nearly state-of-the-art performance in various benchmarks against models with less than 13 billion parameters.
* This model has not been fine-tuned.

We can provide prompts to the model as a standalone question, using the "Instruct: <prompt>\nOutput:" format for more concise answer or in chat format. Phi-2 model is also capable of generating code, wherein we provide a piece of code in the prompt and the model completes it. Adding comments telling the requirements can be helpful.

Phi-2 model has 4 types of execution modes. We are using FP16/Flash-Attention/CUDA mode for quicker reponses on GPUs.