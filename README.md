# Backdoored transformers repo



## Instructions to run the backdoored code

0. Install packages: `pip install torch datasets scikit-learn wandb`
   
1. Install transformers locally: `pip install -e .`

2. Move to examples for text classification: `cd examples/text-classification`.

3. Start training script: `sh run_classification.sh`

4. Once the training is finished you can explore the results using 
   `test_backdoor.ipynb` also located in `examples/text-classification/`j
   