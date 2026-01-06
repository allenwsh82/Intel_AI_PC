# Building An AI ChatBot with LlamaIndex Framework


<img width="1000" alt="AI_ChatBot_RAG_LlamaIndex" src="https://github.com/user-attachments/assets/e6938e23-9593-4cd6-95c0-f8e8fb5dffce">


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
What is the TCO delta in percentage if we compared 15 5th Gen Xeon Processor with 50 AMD EPYC 9554 Processor?

**ChatBot:** 
Based on the provided context information, I can calculate the TCO (Total Cost of Ownership) delta as follows:
According to the text, a fleet of 50 servers based on AMD EPYC 9554 processors has a capital expenditure (CapEx) cost of 1.36𝑎𝑛𝑑𝑜𝑝𝑒𝑟𝑎𝑡𝑖𝑛𝑔𝑒𝑥𝑝𝑒𝑛𝑠𝑒(𝑂𝑝𝐸𝑥)𝑐𝑜𝑠𝑡𝑠𝑜𝑣𝑒𝑟𝑓𝑜𝑢𝑟𝑦𝑒𝑎𝑟𝑠𝑜𝑓
1.36andoperatingexpense(OpEx)costsoverfouryearsof749.7K.
On the other hand, a fleet of 15 servers based on 5th Gen Intel Xeon Platinum 8592+ processors has a CapEx cost of 572𝐾𝑎𝑛𝑑𝑂𝑝𝐸𝑥𝑐𝑜𝑠𝑡𝑠𝑜𝑣𝑒𝑟𝑓𝑜𝑢𝑟𝑦𝑒𝑎𝑟𝑠𝑜𝑓
572KandOpExcostsoverfouryearsof238.3K.
The total savings in TCO can be calculated as follows:
TCO savings = (50 * (1.36+
1.36+749.7K)) - (15 * (572𝐾+
572K+238.3K)) TCO savings ≈ 37,450−
37,450−11,235 TCO savings ≈ $26,215
Now, to find the TCO delta in percentage:
TCO delta = ((TCO savings / (50 * CapEx cost of AMD EPYC 9554)) * 100) TCO delta ≈ ((26,215/(
26,215/(1.36 * 50))) * 100 TCO delta ≈ 62%
Therefore, the TCO delta is approximately 62%.

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

![Rag_Images](https://github.com/user-attachments/assets/ac5b3df6-39a1-4934-bd9d-2d8051584743)
