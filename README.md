# DA5401 End Semester Data Challenge
**Name:** Samyam Rishika  
**Roll Number:** CE22B101  
**Kaggle Username:** lolol707

---

## Challenge Overview
This challenge focuses on metric learning, a machine learning approach that learns how to measure similarity between objects. The task is to build a model that predicts a "fitness" score indicating how well an AI Evaluation Metric Definition aligns with a given Prompt-Response text pair.

## Folder Structure
```bash
├── final_model.ipynb
├── embeddings.ipynb
├── EDA.ipynb
├── inputs (Zip folder - contains all the input files required)
└── README.md # Project description and instructions
```

## How to Run
1. Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/Rishika-28/DA5401-Endsem-Rishika-28.git
cd DA5401-Endsem-Rishika-28
```
2. Run EDA.ipynb followed by embeddings.ipynb (This creates the embeddings required) and now use these as an input to run the final_model.ipynb

## Notes
1. The embeddings are too large to be uploaded, need to be processed from scratch using the embeddings.ipynb. 
2. All the input files (eg: train_data.json, test_data.json) are zipped to inputs file. Load it and change the path accordingly in all the ipynb files wherever required.
3. Need to authorize google/embeddinggemma-300m on huggingface 


