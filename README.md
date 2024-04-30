# Efficient-LLM-Few-Examples-Supervised-Fine-Tuning

This is a final porject repository for Goergia Tech CS7643 (Spring 2024). 

Because we need GPU for this project, we used Google Colab to run our code. 

## Project Abstract 
In-context learning (ICL) in Large Language Models (LLMs) has been shown to be one of their key capabilities. ICL allows to provide a reasoned answer to a question based on a series of examples passed in the context to an LLM, this way providing a more accurate response. However, this comes at the expense of large-context utilization each time a question is asked, which has an associated higher computational cost and time penalty at inference. The project aims to evaluate different recently developed fine-tuning alternatives to ICL: 
- Context Distillation (CD),
- Selective Context Distillation (SCD),
- Virtual Token Embedding Fine-tuning applied with Context Distillation (VTEFT-CD)
- Context Distillation with Low-Ranked Adaptation (LoRA) (CD-LoRA)
- Vanilla Fine-Tuning,
- Pattern-Based Fine-Tuning (PBFT)

We compare them to ICL in terms of accuracy for both in-domain and out-of-domain questions.


## Project Member
- Javier Nieves Remacha (GitHub Account Name: jnremachaGH)
- Go Suzui (GitHub Account Name: gOsuzu)
- Nitesh Agarwal (GitHub Account Name: phantom002)
- Gabriel Martínez Maza (Git Hub Account Name: GarbelMartinez)
