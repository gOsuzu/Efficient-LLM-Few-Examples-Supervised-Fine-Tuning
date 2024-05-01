In this folder, the following files are available:

- "Generate_Embedding_Weight_Change_FineTuning_CD_OPT1.3B_EXP_50tokens" --> notebook that fine tunes only embedding layer and exports the norm of the weight changes to csv in order to further analyze with the DataAnalysis notebook.
- all csv files generated with prior files
- "DataAnalysis_CommonTrainedEmbTokens_GPT3_FORMAT_OPT1.3B_CD_50tokens.ipynb" --> notebook that analyzes the most common tokens found in training only embedding layer
- "VTEFT_CD_OPT1.3B_EXP_50tokens.ipynb" --> notebook that fine tunes a model on selected embbeding tokens only (14 in this case), example for 1 experiment and with model OPT-1.3B
