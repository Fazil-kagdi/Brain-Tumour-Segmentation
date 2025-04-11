## 🚀 Getting Started

### Step 1: Install Dependencies

Install all required libraries using pip:

```bash
pip install numpy nibabel tensorflow matplotlib scikit-learn torch medpy monai segmentation-models-pytorch tqdm
```
> Make sure you're using a Python environment with access to GPU (recommended) and Python 3.8+.

### Step 2: Downloads

## 🧠 Dataset

Download the Brain Tumor Segmentation dataset (BraTS subset) from the link below:

📁 [Download Task01_BrainTumour (Google Drive)](https://drive.google.com/drive/folders/1sxg5YmghJX95YpYhzIZbR6_tevkY-vyn?usp=sharing)

After downloading:
- Place the folder `Task01_BrainTumour` directly into your project root (or wherever your notebook expects them).

---

## 🧮 Pretrained Model Weights

Download the pretrained model weights here:

💾 [Download model_weights.pth (Google Drive)](https://your-google-drive-link-here)

After downloading:
- Place `model_weights.pth` in the same directory as your notebook or in a `weights/` folder if your code expects that.

### Step 3: Run the Notebook

Open the Jupyter notebook and run all the cells sequentially.

If you want to train from scratch, simply run all cells in order.

If you want to use the pretrained model directly:

Run all cells up to the one marked "1st stage training".

Then skip to the "Data Visualization" cell and run from there to visualize the segmentation results.
