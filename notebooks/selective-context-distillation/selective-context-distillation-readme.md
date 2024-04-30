This folder contains:

- "Generate_TrainData_SelectiveContextDistillation_50tokens" --> notebook to generate csv file that contains the top probabilities to train a selective-CD model (fine-tuning in different notebook) 
- csv files corresponding to each one of the outputs generated from previous notebook for each model size,
- "SelectiveCOntextDistillation_OPT350M_50tokens" --> notebook that reads the corresponding csv file for its model size and finetunes the model according to selective context distillation. Here uploaded just one example, the rest of data is generated changing inputs at the top of the notebook.
