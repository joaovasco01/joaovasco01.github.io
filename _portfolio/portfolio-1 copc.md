---
title: "AI-Powered Virtual Fitting with Stable Diffusion"
excerpt: "Developing a fine-tuned Stable Diffusion model with LoRAs to enable realistic virtual try-ons."
collection: portfolio
---

## Overview  
This project explores **AI-powered virtual fitting**, leveraging **Stable Diffusion fine-tuning and LoRA models** to realistically apply a photographed piece of clothing onto different individuals. By **combining inpainting, LoRA training, and model fine-tuning**, the system generates highly accurate and natural-looking **virtual try-on results**.

## Key Features  
- **Fine-Tuned Stable Diffusion Models** – Trained AI models to seamlessly apply a specific clothing piece onto different body types.  
- **LoRA-Based Training** – Enhanced the **base model with LoRAs** for improved adaptability to various styles and textures.  
- **Inpainting for Clothing Application** – Using **masking and inpainting techniques** to blend the clothing piece naturally onto subjects.  
- **Photorealistic Rendering** – Ensuring that lighting, texture, and perspective match the original clothing item.  

## Process  
1. **Photography & Data Collection** – Captured high-resolution images of the target clothing piece.  
2. **LoRA Training** – Fine-tuned a **Stable Diffusion model** to learn the unique features of the garment.  
3. **Inpainting Pipeline** – Used **masked inpainting** to overlay the clothing onto new subjects while preserving natural body structure.  
4. **Model Refinement** – Iteratively trained and adjusted LoRAs to **improve fabric realism and adaptability**.  
5. **Final Output** – Generated realistic virtual try-on images where individuals appear to be **wearing the target clothing item**.  

## Sample Results  
**Same piece of cloth on 2 different models :**  
![Virtual Try-On Result Model 1](/images/virtual-fitting-1.png) 

The second model was pre-photographed and was wearing different clothing.

![Virtual Try-On Result Model 2](/images/virtual-fitting-2.png)  



## Future Improvements  
- **Expanding Dataset** – Increasing the number of garments and testing with different clothing categories.  
- **Real-Time Virtual Try-On** – Exploring integration with **live webcam input** for instant outfit previews.  
- **Refining Textures & Fabric Physics** – Further improving **how fabric folds, drapes, and reacts to body movements**.  

---
