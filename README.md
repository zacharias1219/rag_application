# rag_application

## Architecture

Pdf's will be stored in vectorstore
Using Langchain to harness LLM's using AWSBedrock
Data Ingestion: Read all the pdf's

1. Prepare the documents: Split the documents into chunks and create embedding(Amazon Titan) into FAISS vectorstore

2. Ask Question: When question is asked, similarity search teakes place, relevant chunks are given to the LLM and the answer is generated.

## Steps

To use this application, follow these steps:

1. Clone the repository that you have forked:

    ```shell
    git clone  https://github.com/username/rag_application
    ```

2. Go to app.py file:

    ```shell
    cd app.py
    ```

3. Start the Streamlit interface by running the following command:

    ```shell
    streamlit run app.py
    ```

4. Access the rag application through the user-friendly interface and provide your prompts.
