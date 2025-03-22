# 🚀 Hugging Face DETR Object Detection

This project demonstrates **object detection** using the **DETR (DEtection TRansformer) model** from Hugging Face. The model detects objects in an image and returns bounding boxes along with class labels and confidence scores.

## 📂 **Project Structure**
```
huggingface-detr/
│── .env  # Stores API Key (Not pushed to GitHub)
│── README.md
│── requirements.txt
│── main.py
│── images/
│   └─ image.jpg  # Example image
```

---

## 🛠️ **Installation & Setup**

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/dishapawarkhausi/object-detection.git
cd object-detection/huggingface-detr
```

### 2️⃣ **Create a Virtual Environment (Optional but Recommended)**
```bash
python -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate  # For Windows
```

### 3️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 4️⃣ **Set Up Your API Key**  
Create a `.env` file in the project directory and add your Hugging Face API token:
```ini
HUGGINGFACE_API_KEY=your_api_token_here
```

⚠️ **Important:** Never share your API key or commit `.env` to GitHub.

---

## 🚀 **Usage**
Run the script with an image of your choice:
```bash
python main.py --image images/image.jpg
```
This will display the image with detected objects and their bounding boxes.

---

## 📝 **Configuration**
Modify `main.py` to change:
- The model endpoint (if needed)
- Image file paths
- Visualization settings

---

## 🎯 **Contributing**
Want to improve this project?  
- **Fork** this repository  
- **Create a branch** (`git checkout -b feature-xyz`)  
- **Commit your changes** (`git commit -m "Add new feature"`)  
- **Push and submit a PR** (`git push origin feature-xyz`)  

---

## 🏆 **Credits**
- Model: [DETR (facebook/detr-resnet-50)](https://huggingface.co/facebook/detr-resnet-50)
- API: [Hugging Face Inference API](https://huggingface.co/inference-api)
- Libraries: `requests`, `dotenv`, `Pillow`, `matplotlib`

---

## 🐝 **License**
This project is open-source under the [MIT License](LICENSE).

