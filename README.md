# SmartFabric-AI-System
An AI-powered multi-model system that classifies dress type, identifies fabric material, and detects fabric defects using deep learning and CNN models.

## Features  
- Dress Type Classification (Dhoti, Frock, Salwar, Saree, Shirt)  
- Fabric Material Detection (25+ fabric types)  
- Fabric Defect Detection (Hole, Horizontal, Vertical, Lines, No Defect)  
- Confidence-based predictions  
- Single image → multiple AI outputs  

## Tech Stack   
- Python   
- TensorFlow / Keras  
- CNN (Custom Deep Learning Models)  
- Google Colab  
- NumPy  

## Project Structure  

SmartFabric-AI-System/   
│   
├── notebooks/   
│         ├── dress_model.ipynb  
│         ├── fabric_model.ipynb  
│         ├── defect_model.ipynb  
│         └── predict.ipynb   
│  
├── README.md  

## Models (Google Drive Links)   
- Dress Model:
 https://drive.google.com/file/d/12TKvKDaJbbkmN1P6hknKxWLHagZDsHin/view?usp=drive_link
- Fabric Model:
 https://drive.google.com/file/d/1lYOY3EBWW6gNc_AKp6-hjNSL3W_KwXTy/view?usp=drive_link  
- Defect Model:
 https://drive.google.com/file/d/1dDZPId8C3S4hf1gf7YLOFOhZ99jXmJvg/view?usp=drive_link

 ## How to Run  
1. Open Google Colab  
2. Upload or open predict.ipynb  
3. Download models from Drive links  
4. Update model paths inside notebook  
5. Run all cells    
6. Upload image → Get predictions  

## Output Example  
- Dress: Saree
- Fabric: Cotton  
- Defect: No Defect
  
## Project Workflow

Input Image → Preprocessing 
→ Dress Model
→ Fabric Model
→ Defect Model
→ Final Combined Output

## Note  
- Models are not uploaded to GitHub due to size limits (>25MB)
- Use provided Google Drive links to access trained models
