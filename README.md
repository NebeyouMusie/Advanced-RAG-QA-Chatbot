# Advanced RAG Q&A Chatbot
- In this project I have built an advanced RAG Q&amp;A chatbot with chain and retrievers using Langchain


## Description
- **Retrievers**: A retriever is an interface that returns documents 
 given an unstructured query. It is more general than a vector store.
- A retriever does not need to be able to store documents, only to 
 return (or retrieve) them. Vector stores can be used as the backbone
 of a retriever, but there are other types of retrievers as well. 
- **Retrieval chain**:This chain takes in a user inquiry, which is then passed to the retriever to fetch relevant documents. Those documents (and original inputs) are then passed to an LLM to generate a response

## Libraries Used
- langchain==0.1.20
- langchain-community==0.0.38
- langchain-google-genai==1.0.3
- faiss-cpu==1.8.0
- pypdf==4.2.0

## Installation
 1. Prerequisites
    - Git
    - Command line familiarity
 2. Clone the Repository: `git clone https://github.com/NebeyouMusie/Advanced-RAG-QA-Chatbot.git`
 3. Create and Activate Virtual Environment (Recommended)
    - `python -m venv venv`
    - `source venv/bin/activate`
 4. Navigate to the projects directory `cd ./Advanced-RAG-QA-Chatbot` using your terminal
 5. Install Libraries: `pip install -r requirements.txt`
 6. Open and run all cells in the `retriever_chain.ipynb` notebook then enter your google api key
 7. Or you can download the PDF in the `data` directory and the `retriever_chain.ipynb` Notebook from the `notebook` directory in the repository, upload those files and notebook to Google Collab then run all the cells in the `retriever_chain.ipynb` Notebook then enter your google api key

## Collaboration
- Collaborations are welcomed ❤️

## Acknowledgments
 - I would like to thank [Krish Naik](https://www.youtube.com/@krishnaik06)
   
## Contact
 - LinkedIn: [Nebeyou Musie](https://www.linkedin.com/in/nebeyou-musie)
 - Gmail: nebeyoumusie@gmail.com
 - Telegram: [Nebeyou Musie](https://t.me/NebeyouMusie)

