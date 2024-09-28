# End_To_End-Medical-Chatbot-Using-Llama2

# Step 1 to run the project
'''bash
conda create -n mchatbot python=3.8 -y
'''
conda activate mchatbot


''' pip install -r requirements.txt
'''


# Techstack Used:
Python
LangChain
Flask
Meta Llama2
Pinecone

# 3. Create a .env file in the root directory and add your Pinecone credentials 
4. Download the quantize model from the link provided in model folder & keep the model in the model directory:
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main


# 5. # run the following command
python store_index.py

open up localhost: