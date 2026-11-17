# Named Entity Recognition using Hugging Face

## Project Overview
This project uses a pretrained BERT-based Named Entity Recognition (NER) model from Hugging Face to identify and classify named entities in text.

## Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- Google Colab

## Features
- Identifies named entities in text
- Extracts person names, organizations, and locations
- Displays entity types and confidence scores
- Uses a pretrained Transformer model

## Model Used
`dslim/bert-base-NER`

## How It Works
1. Load the pretrained NER model using the Hugging Face pipeline.
2. Provide input text.
3. Pass the text to the model.
4. Extract recognized entities and their categories.
5. Display the entities with confidence scores.

## Example
**Input:**
"Nithin works at Google in Hyderabad."

**Expected entities:**
- Nithin — Person
- Google — Organization
- Hyderabad — Location

Actual predictions depend on the model output.

## How to Run
1. Open `ner_using_huggingface.ipynb` in Google Colab.
2. Run the installation cell.
3. Execute the remaining cells.
4. Change the input sentence to test other examples.

## Repository Structure
```text
ner-using-huggingface/
│
├── ner_using_huggingface.ipynb
└── README.md
```

## Learning Outcome
Learned how to apply pretrained Transformer models for Named Entity Recognition using Hugging Face pipelines.
