This is a simple RAG implementation on from this [dataset](https://www.kaggle.com/datasets/shimizulk04/anime-dataset) to retrieve Anime Information and answer queries from users.

---

### How to use:

If you are poor and cannot afford GPU, you can use Kaggle Notebook with GPU T4x2 turned on to run the `.ipynb` file. If your device already provided CUDA for GPU usage, then just download the notebook and run it.

For anyone who imported it to Kaggle Notebook, you need to import the `anime_faiss.index` file to `input` section of your Notebook. However, you can run it without the `.index` file, but it will take some time to embedding all of the sentences from the dataset.

You can change the models for RAG and LLM as long as your devices can handle it well. If you use my preset model, remember to get permission from huggingface to run.
