# Arabic Handwriting Recognition

I built this OCR system to recognize handwritten Arabic text using deep learning. The system takes images of Arabic handwriting, fixes distortions, detects text lines, segments words, then uses a ResNet50V2 model with Bi-LSTM networks to recognize the text achieving 97% accuracy.


## Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/5cbaed0c-9a78-4f2e-b6d7-f262328bf529" alt="Main Page" width="600"/>
  <br>
  <em>Main Application Page</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/557d9d83-c279-46c4-822f-666b5919275b" alt="OCR Model" width="600"/>
  <br>
  <em>Handwriting Recognition in Action</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/de932111-2937-423b-9a42-c696a2706d58" alt="Exam Grader" width="600"/>
  <br>
  <em>Exam Grading Feature</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/95e18c1f-969d-48c5-a584-85e50b45d467" alt="System Diagram" width="600"/>
  <br>
  <em>Full System Flow</em>
</p>

## Installation

```bash
# Clone the repository
git clone https://github.com/AHR-OCR2024/Arabic-Handwriting-Recognition.git
cd Arabic-Handwriting-Recognition/Application

# Install backend dependencies
pip install -r requirements.txt

# Install frontend dependencies
npm install

# Download pretrained models
# Link: https://mega.nz/file/0NZlkYAY#lFYQzTWaotIOJ7tYZ5ufPLLbVUP1B5hydpL3y9aPik0
# Place them in Application/Backend/Models

# Run the application (use two terminals)
# Terminal 1 - Backend
python ./Backend/Backend.py

# Terminal 2 - Frontend  
npm run dev
