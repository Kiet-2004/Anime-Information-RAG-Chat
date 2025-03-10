### Simple RAG Implementation for Anime Information Retrieval  

This repository provides a simple Retrieval-Augmented Generation (RAG) implementation using [this dataset](https://www.kaggle.com/datasets/shimizulk04/anime-dataset) to retrieve anime-related information and respond to user queries.  

---
### How to Use  

- **Running on Kaggle**:  
  If you do not have access to a GPU, you can use Kaggle Notebooks with a **T4x2 GPU** enabled to run the `.ipynb` file.  

- **Running on a Local Machine**:  
  If your device supports CUDA for GPU acceleration, you can download the notebook and run it locally.  

- **Using the FAISS Index**:  
  If you are running the notebook on Kaggle, ensure that the `anime_faiss.index` file is uploaded to the **"Input"** section of your notebook. Running the notebook without this index file is possible, but embedding all sentences from the dataset will take quite a long time.  

- **Model Customization**:  
  You may replace the default models for retrieval and language generation as long as your device can handle them efficiently. If you choose to use the preset models, ensure that you have the necessary permissions from **Hugging Face** to access and run them.  
