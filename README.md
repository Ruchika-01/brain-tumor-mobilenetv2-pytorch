# Brain Tumor MRI Classification (PyTorch MobileNetV2 + Grad-CAM)
This project performs **4-Class Brain Tumor MRI Classification** using **MobileNetV2** (Transfer Learning) in **PyTorch**.

### 🧠 Classes
- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

###  Highlights
- **Test Accuracy**: ~**99.4%**
- **Balanced F1-score > 0.98** across all classes
- **Explainability** via **Grad-CAM Heatmaps**
- Lightweight model ideal for **edge deployment** (MobileNetV2)
- Exported to **TorchScript & ONNX** for deployment workflows

### Dataset
Kaggle: Brain Tumor MRI Dataset (4 classes)  
Train/Val/Test split using patient-independent directory sampling.

###  Explainability
Grad-CAM heatmaps were generated to show where the model is focusing inside the brain region, ensuring **clinical trust** and safety.


###  How to run
1. Upload dataset to Drive
2. Open notebook in Colab
3. Run all cells to:
   - Train model
   - Evaluate performance
   - Generate Grad-CAM outputs
   - Export ONNX/TorchScript models

**Notebook:** `BrainTumor_MobileNetV2.ipynb`

###  Artifacts
Saved to Drive:
- ✅ Best Model Weights (`best_model.pt`)
- ✅ TorchScript export
- ✅ ONNX export
- ✅ Gallery & Misclassified Samples

---



*This work demonstrates deep learning in healthcare with a focus on explainability and trustworthy AI.*


📌 *This work demonstrates deep learning in healthcare with a focus on explainability and trustworthy AI.*
