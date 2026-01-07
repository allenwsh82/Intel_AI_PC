# Building An AI ChatBot with LlamaIndex Framework

![Dell_AI_ChatBot](https://github.com/user-attachments/assets/e8c0fa1c-1fe3-4324-ac63-5f20cc8899ea)


**Details of this demo:**

RAG Framework: LlamaIndex (https://www.llamaindex.ai/) [Production ready LLM application]

Model Serving Framework / Libraries : Ollama (https://ollama.com/)

User Interface : Streamlit (https://streamlit.io/) 

Document type used for RAG: PDF Document
LLM Model: Phi-3-mini-4k-instruct-int4-ov

Embedding Model: BAAI/bge-large-en-v1.5

Vector Store: In Memory from Llama Index (https://lnkd.in/gZWqXRvv)

**Hardware Configuration:**

CPU : Intel Core Ultra 7
RAM usage: 12GB (During RAG Prompt), 5GB (During document indexing)

**Observation:**

**Prompt:** 
Tell me about OpenVINO?

**ChatBot:** 
OpenVINO is a suite of tools and software developed by Intel to optimize and deploy deep learning models for inference on Intel hardware. It includes the Inference Engine, which is a high-performance inference engine that can run on Intel CPUs and GPUs. The toolkit also provides the Model Optimizer, which can convert models to the Inference Engine format, and the Post-Training Optimization Toolkit (POT), which can quantize models to reduce their precision and improve inference speed.

The OpenVINO Model Zoo is a collection of pre-trained models that can be used for various deep learning tasks, such as object detection, semantic segmentation, and more. The Model Zoo also includes demos and scripts to help users develop and deploy high-performance inference applications.

To use OpenVINO, users can install it on their target system, which should meet the requirements specified in the installation guides. Once installed, users can use the Model Optimizer to convert models to the Inference Engine format, and the POT to quantize models. The Inference Engine can then be used to run inference on the optimized models, and the results can be visualized using the provided tools.

In summary, OpenVINO is a powerful toolkit for optimizing and deploying deep learning models on Intel hardware, with a focus on inference speed and efficiency. It includes the Inference Engine, Model Optimizer, and POT, as well as the Model Zoo and various demos and scripts to help users get started.

**How to run llm with web scraping with RAG Demo:**

1) Clone the project:
   ``` 
   git clone https://github.com/allenwsh82/Intel_AI_PC

   ```
   
2) Create a new environment for this project:
   ```
   python -m venv rag_env
   ```
   
3) Activate the environment:
   ```
   source rag_env/bin/activate
   ```
   
4) Setup the environment with all the dependencies:
   ```
   pip install -r requirements.txt
   ```
   
5) Run the demo script by this command:
   ```
   streamlit run inference.py
   ```

Screen shot of how the Demo's GUI looks like 

![LNL_AI_PC](https://github.com/user-attachments/assets/b3fac619-21f6-45c9-aa5b-04777543dcec)

