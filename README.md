# Modelling Large Language Models Over Joint Source Channel Codec for Semantic Communication

For 3GPP recognition of new semantic communication (SemCom) paradigms and to support ITU-T standardization, an independent, interoperable implementation is crucial. We develop and implement a novel SemCom approach by integrating advanced large language models (LLMs) into the Joint Source Channel Codec (JSCC) framework. Our proposed framework and the accompanying open implementation, significantly enhance our understanding of the practical challenges and operationalization efficiency with precision. We detailed our open implementation of Llama-2 within JSCC, available as a dynamically loadable module. Our SemCom research and implementation aim to develop a general-purpose, text-based assistant aligned with human values—being helpful, honest, and harmless. Our initial efforts focus on studying simple baseline techniques and evaluations, such as prompting. We provide a summary of the LLM-JSCC framework to assist others in developing interoperable versions. We propose an innovative use of context distillation for prompting that fills a gap often overlooked in existing JSCC approaches. Experiments confirm our implementation's expected SemCom behaviour, highlighting factors that influence its dynamic performance. Through extensive experimental evaluations, we observed notable improvements in the effectiveness and efficiency of SemCom compared to existing solutions, offering a scalable and efficient framework that aligns with imminent objectives and paves the way for further innovations in SemCom.


#### Conceptual view of the proposed SemCom Networking: Llama-2 over JSCC. The proposed notion of jointly training models centrally while deploying them in a distributed manner resonates strongly with the encoder-decoder transformer model, presenting a promising avenue for streamlined communication
![Conceptual view of the proposed SemCom Networking: Llama-2 over JSCC. The proposed notion of jointly training models centrally while deploying them in a distributed manner resonates strongly with the encoder-decoder transformer model, presenting a promising avenue for streamlined communication.](https://github.com/rajayarli/LLAMA2-JSCC/blob/8703621e24fbfd050020b62a46cb09a78915d5f5/llamajscc.png)

#### Algorithm 1: utilization of Llama-2 as a tool for understanding before transmission in the JSCC framework
We provide only the essential details of our
implementation code to help clarify and track our convergent
design and demonstrate the core implementation pseudocode
of the proposed framework. For in-depth exploration, we
suggest visiting the complete
codebase developed in this research.
Observe in Algorithm 1 that at the heart of our solution is
the utilization of Llama-2 as a tool for understanding before
transmission and after reception in the JSCC framework

![In Algorithm 1, we provide only the essential details of our
implementation code to help clarify and track our convergent
design and demonstrate the core implementation pseudocode
of the proposed framework. For in-depth exploration, we
suggest visiting the complete
codebase developed in this research.
Observe in Algorithm 1 that at the heart of our solution is
the utilization of Llama-2 as a tool for understanding before
transmission and after reception in the JSCC framework.](https://github.com/rajayarli/LLAMA2-JSCC/blob/ec3ce6ff59994dabf3a37d5b0982031865f31a20/Algorithm11.png)


#### Algorithm 2: A high-level view of our framework for context distillation and toxicity analysis
![In Algorithm 2](https://github.com/rajayarli/LLAMA2-JSCC/blob/ec3ce6ff59994dabf3a37d5b0982031865f31a20/Algorithm22.png)


##### Proof of Concept; Google Colab link for Preliminary Analysis:
https://colab.research.google.com/drive/1GT-5rk0hkYlRwe8TXLblnePDPpCOKzEw#scrollTo=YMfc1pytcJ7Q 
Youtube link for a simple code review:
https://youtu.be/nTJZis5JKrE 

