# Finetune-Phi-2

1. Choose Microsoft's phi-2 model. Parameter count: 2.7 billion
2. Generated 10 example of dataset. file name: shop_chat.txt
3. dataset_prep.ipynb notebook is used for prepare raw data to convert phi-2 training suitable. shop_chat.jsonl is the phi-2 suitable file.
4. training.ipynb notebook has the trainig code for phi-2 model using my own generated dataset.
5. model was quantized using bitsandbytes library.
6. Model was finetuned using QLoRA. 
