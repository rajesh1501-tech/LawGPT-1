<h1 align="center">LawGPT - RAG based Generative AI Attorney Chatbot</h1>
<h3 align="center">Know Your Rights! Better Citizen, Better Nation!</h1>

<p align="center">
<img src="https://github.com/harshitv804/LawGPT/assets/100853494/ecff5d3c-f105-4ba2-a93a-500282f0bf00" width="700"/>
</p>

## About The Project
LawGPT is a RAG based generative AI attorney chatbot that is trained using Indian Penal Code data. This project was developed using Streamlit LangChain and TogetherAI API for the LLM. Ask any questions to the attorney and it will give you the right justice as per the IPC. Are you a noob in knowing your rights? then this is for you!
<br>

### Check out the live demo on Hugging Face <a href="https://huggingface.co/spaces/harshitv804/LawGPT"><img src="https://static.vecteezy.com/system/resources/previews/009/384/880/non_2x/click-here-button-clipart-design-illustration-free-png.png" width="120" height="auto"></a>

## Getting Started

#### 1. Clone the repository:
   - ```
     git clone https://github.com/harshitv804/LawGPT.git
     ```
#### 2. Install necessary packages:
   - ```
     pip install -r requirements.txt
     ```
#### 3. Run the `ingest.py` file, preferably on kaggle or colab for faster embeddings processing and then download the `ipc_vector_db` from the output folder and save it locally.
#### 4. Signup and get 25$ of free credit (or just pay for it If you wish to use for long-term, they are more cheaper than OpenAI API. You can also use other LLMs or APIs if you wish so. Check this link: [python.langchain.com/docs/integrations/llms](https://python.langchain.com/docs/integrations/llms) for more options.), and then set TogetherAI API Key in environment variable in python. 
   - ```
      os.environ["TOGETHER_API_KEY"] = "YOUR_TOGETHER_API_KEY"`
     ```
   - If you are going to host it in streamlit, huggingface or other...
      - Save it in the secrets variable provided by the hosting with the name `TOGETHER_API_KEY` and key as `YOUR_TOGETHER_API_KEY`.

#### 5. To run the `app.py` file, open the CMD Terminal and and type `streamlit run FULL_FILE_PATH_OF_APP.PY`.

## Contact
If you have any questions or feedback, please reach out to [harshitvenkatesan88@gmail.com]
