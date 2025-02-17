# Deepfake-And-fraud-Detection

The **Media Analysis App** is a powerful tool designed to detect deepfake videos and images, analyze live audio for fraud or spam detection, and classify uploaded audio files for authenticity. It uses **Machine Learning, Computer Vision, and Generative AI** to provide real-time analysis and classification.

## **Features**  
- **Deepfake Video Detection** – Extracts frames from uploaded videos and analyzes them using AI models to determine authenticity.  
- **Deepfake Image Detection** – Identifies whether an uploaded image is real or manipulated.  
- **Live Audio Analysis** – Records and processes live audio to classify it as **spam, fraud, or genuine** using Generative AI.  
- **Spam Audio Detection** – Analyzes uploaded audio files and detects fraudulent activities based on call metadata and behavior patterns.  

## **Technologies Used**  
- **Streamlit** – Interactive web application for easy user interaction.  
- **OpenCV & PIL** – Image and video processing.  
- **Google Gemini AI** – Advanced Generative AI model for audio and text analysis.  
- **pyaudio & wave** – Real-time audio recording and processing.  

## **How It Works**  
1. **User uploads a video or image**, and the system classifies it as real or deepfake.  
2. **For live audio**, the app records voice input, analyzes it, and provides a classification.  
3. **For spam audio detection**, users upload an audio file, and AI determines whether it's fraud, spam, or legitimate.  

## **Installation & Setup**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:  
   ```bash
   streamlit run app.py
   ```

## **Usage**  
- Upload a video or image to detect deepfakes.  
- Record or upload an audio file for fraud/spam detection.  
- Get instant AI-powered analysis results.  
