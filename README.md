# 🕯️ Ofrenda

A remembrance writer for Día de los Muertos. Enter a loved one's name,
favorite foods, a song and a memory, and an open-weight model writes
a short, warm remembrance.

Built for the Hacktoberfest 2026 DEV Challenge, Week 4: Ghost in the Machine.

## How it works
- Model: Gemma 3 (4B), served with Ollama
- Interface: Gradio
- Notebook: `ofrenda.ipynb`, run on Google Colab with a T4 GPU
- A system prompt tells the model to use only the details you give it

## Run it yourself
1. Open `ofrenda.ipynb` in Colab
2. Choose Runtime > Change runtime type > T4 GPU
3. Run all cells and open the public link

## Why open
The same code runs fully offline with Ollama on your own computer,
so family stories never need to leave your device.
