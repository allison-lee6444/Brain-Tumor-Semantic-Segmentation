# Brain-Tumor-Semantic-Segmentation

The code to reproduce our results is separated in different notebooks. 
Please be aware that all of our code has only been tested on the Colab
environment because the size of the models and the amount of computation 
power necessary. 

We recommend you to run the notebooks in this sequence to replicate our process:

1. ClipSeg reproduction
2. AutoSAM fine-tuning (optional)
3. Prompt generation 
4. SAM 2 fine-tuning
5. MicroSAM fine-tuning
6. Evaluation


If you prefer to run it locally, first turn the using_colab flag to False 
and install [mamba](https://mamba.readthedocs.io/en/latest/installation/mamba-installation.html)

Run this to install all your package requirements.
    
    pip install -r requirements.txt