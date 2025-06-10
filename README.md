# Audio-Image-GENAI
 1. Project Title
    # Audio to Image Generation using GenAI (Stable Diffusion)
2. Project Description
   This project takes an audio input, converts it into a meaningful text prompt (manually or via speech-to-text),
   and then uses a Generative AI model (Stable Diffusion v1.5) to generate a realistic image based on the prompt.
   Built using Hugging Face's `diffusers` library in Google Colab with GPU acceleration (CUDA).
3. Demo
   🎤 Recognized Text: rose flowers
   ![image](https://github.com/user-attachments/assets/7265e6bc-b9db-4569-a72f-9766a8bc7392)
4. Technologies Used
   ## 🛠️ Technologies
- 🧠 [Hugging Face diffusers](https://huggingface.co/docs/diffusers/)
- 🎨 Stable Diffusion v1.5 (`runwayml/stable-diffusion-v1-5`)
- 🐍 Python (Colab)
- 🎧 Manual Audio Upload (optionally can use Whisper for speech-to-text)
- ⚡ CUDA GPU (in Google Colab)
5. Installation
  ## 📦 Installation (Optional if using Colab)
  Clone the repository:
                  git clone https://github.com/pallaamulya/audio-to-image-genai.git
                  cd audio-to-image-genai
6. Usage
  ## 🚀 How to Use
     1. Open the Colab notebook: `Audio to Image Using GENAI.ipynb`
     2. Upload an audio file manually
     3. Enter a text prompt (either by transcribing audio or writing it yourself)
     4. The model will generate and display an image
     5. The image is saved in the `generated_images/` folder
7. Project Folder Structure
   audio-to-image-genai/
   ├── Audio to Image Using GENAI.ipynb
   ├── README.md
8. Author
   ## 👩‍💻 Author

- **Name**: Palla Amulya  
- **GitHub**: [pallaamulya](https://github.com/pallaamulya)  
- **Technology Stack**: Data Science, Web Development, Deep Learning


