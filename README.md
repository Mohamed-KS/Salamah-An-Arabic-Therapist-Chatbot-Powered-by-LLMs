Hello :)
Feel free to use the dataset and the model how you'd like

This is my hugging face account: https://huggingface.co/mkay8
Here you can find the models (there are multiple versions) and the dataset

The process of finetuning is very simple with the help of unsloth (library)

The dataset was collected from Altibbi.com and IslamWeb after we were granted permission

We cleaned the dataset by removing special symbols, some punctuation, and some numbers.

The Dataset_format.ipynb file is where we added the special tokens. This is a very important step. Whenver you finetune a model, the data to be fed into the model must have a certain template that shows the model which part of the model is said by the user, which part is said (or to be said) by the AI assistant, and which part is the prompt. You can experiment with different templates. The one I used was said to be the best one for Llama3-Instruct

The GRADPROFINETUNE.ipynb is where the finetuning happens. The file was created by unsloth but I changed some hyperparameters and used my own dataset.

Please feel free to reach out if you have any questions!
