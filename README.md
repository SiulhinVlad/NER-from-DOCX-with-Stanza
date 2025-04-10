# Named Entity Recognition  

The purpose of this tutorial is to demonstrate how to extract **named entities** from `.docx` files using [Stanza](https://stanfordnlp.github.io/stanza/) (Stanford NLP Toolkit). This guide shows how to load a Word document, analyze it with a pretrained NLP (Natural Language Processing) model, and export the results to `.txt` files.

This method supports **over 70 languages**, but we focus specifically on **Ukrainian** and **Russian** as example languages. No prior programming knowledge is required to follow. All necessary code and instructions are provided inside the notebook.

---

### What This Tutorial Includes

- Loading and reading text from `.docx` files using Python
- Setting up and using Stanza for Named Entity Recognition (NER)
- Detecting and extracting **person** and **location** entities from text
- Exporting the extracted entities to organized `.txt` output files

---

## Language Support

This tutorial supports:

- **Ukrainian** 
- **Russian** 

You can easily switch between them by changing one line in the notebook.

> Note: Stanza will automatically download the required models the first time you run it.

---

## Input & Output

**Input:**
- A `.docx` file containing Russian or Ukrainian narrative or interview text

**Output:**
- text file with a list of **unique persons** found in the text
- text file with a list of **unique locations** found in the text

---

## How to Use

This tutorial is designed to be run in **Google Colab**, so no local Python installation is required.

To open the notebook in Colab, click the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pDIglQ5g6pftn7xVZEl7KtkNfd8eF4w5?usp=sharing)

> Note: You’ll need to upload your `.docx` file into the Colab environment or connect Colab to your Google Drive.

---

## 🛠 Software Requirements

This tutorial was developed with **Python 3.9** and uses the following libraries:

- `python-docx`
- `stanza`
- `torch`
- `numpy`

To install the required libraries manually:

```bash
pip install python-docx stanza torch==2.5.0 numpy
