# gemini_all..

Main.py and requirements.txt and pdf data belongs to "**End To End Document Q&A RAG App With Gemma And Groq API**"

**NOTE:**
**GROQ API**

Groq is used for Inference because of LPU (Language Processing Unit)
The Groq LPU Inference Engine
LPU Inference Engines are designed to overcome the two bottlenecks for LLMs–the amount of compute and memory bandwidth. 
An LPU system has as much or more compute as a Graphics Processor (GPU) and reduces the amount of time per word calculated, 
allowing faster generation of text sequences. With no external memory bandwidth bottlenecks an LPU Inference Engine delivers 
orders of magnitude better performance than Graphics Processor. 

**Some important info about GROQ**

**What is LPU Inference Engine?**

An LPU Inference Engine, with LPU standing for Language Processing Unit™, 
is a new type of end-to-end processing unit system that provides the fastest inference for computationally 
intensive applications with a sequential component to them, such as AI language applications (LLMs).

**Why is it so much faster than GPUs for LLMs and GENAI?**

The LPU is designed to overcome the two LLM bottlenecks: compute density and memory bandwidth. 
An LPU has greater compute capacity than a GPU and CPU in regards to LLMs. This reduces the amount of time per word calculated, 
allowing sequences of text to be generated much faster. Additionally, eliminating external memory bottlenecks enables the 
LPU Inference Engine to deliver orders of magnitude better performance on LLMs compared to GPUs.

For a more technical read about our architecture, download our ISCA-awarded 2020 and 2022 papers. 

**Does Groq run standard machine learning frameworks?**

Groq supports standard machine learning (ML) frameworks such as PyTorch, TensorFlow, and ONNX for inference. 
Groq does not currently support ML training with the LPU Inference Engine.

For custom development, the GroqWare™ suite, including Groq Compiler, offers a push-button experience to get 
models up and running quickly. For optimizing workloads, we offer the ability to hand code to the Groq architecture and 
fine-grained control of any GroqChip™ processor, enabling customers the ability to develop custom applications and maximize their performance.

#**PaliGemma**

PaliGemma is a lightweight open vision-language model (VLM) inspired by PaLI-3, and based on open components 
like the SigLIP vision model and the Gemma language model. PaliGemma takes both images and text as inputs and 
can answer questions about images with detail and context, meaning that PaliGemma can perform deeper analysis of 
images and provide useful insights, such as captioning for images and short videos, object detection, and reading text 
embedded within images.

There are two sets of PaliGemma models, a general purpose set and a research-oriented set:

******PaliGemma ******
General purpose pretrained models that can be fine-tuned on a variety of tasks.
****PaliGemma-FT ********- Research-oriented models that are fine-tuned on specific research datasets.

**Important:** Most PaliGemma models require tuning in order to produce useful results, except for the paligemma-3b-mix variant. 
Make sure you perform fine-tuning on these models and test the output before deploying them to end users.

**Key benefits include:**

Multimodal comprehension
Simultaneously understands both images and text.

Versatile base model
Can be fine-tuned on a wide range of vision-language tasks.

Off-the-shelf exploration
Comes with a checkpoint fine-tuned on on a mixture of tasks for immediate research use.
