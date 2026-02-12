# AI4009 – Assignment No. 1  
**Image Captioning with Seq2Seq on Flickr30k**

**Student:** F223413  
**Course:** Generative AI  
**Semester:** Spring 2026  

## Model
- Encoder: ResNet50 features → Linear(2048→512)  
- Decoder: LSTM-based Seq2Seq  
- Training: 20 epochs, Adam lr=3e-4  
- Final loss: Train ~1.36, Val ~2.35  
- BLEU (300 samples): 0.0256  

## Demo
Public Gradio demo: https://b0a03939b369ba76c5.gradio.live  

## Files
- `AI_ASS01_22F_3413.ipynb` – full notebook  

