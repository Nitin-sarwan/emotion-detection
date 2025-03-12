# emotion-detection
### *Approach to Building the Speech & Text Emotion Detection System*

1. **Technology Stack Selection** 
   - Used *Streamlit* to create an interactive web app for real-time emotion detection.  
   - Chose *Whisper* (by OpenAI) for accurate *speech-to-text transcription*.  
   - Utilized *Joblib* to load a pre-trained *text emotion classification model*.  
   - Implemented *Altair* for *visualizing emotion probabilities*.  
   - Integrated *Torch* for handling deep learning dependencies.

2. **Emotion Detection from Text**
   - Created a *text input form* where users enter text.  
   - The input is passed to a *pre-trained text emotion model* (loaded with Joblib).  
   - The model predicts the *dominant emotion* and provides *confidence scores*.  
   - The results are *visualized using Altair* for better interpretation.

3. **Speech-to-Text Processing**  
   - Allowed users to *upload an audio file* (mp3, wav, m4a).  
   - Used *Whisper* to transcribe the audio into text.  
   - Displayed the transcribed text in *Streamlit* for verification.

4. **Emotion Detection from Speech**
   - Passed the *transcribed text* to the same *emotion detection model*.  
   - Predicted the *emotion* from the transcribed text.  
   - Displayed the emotion with an *emoji representation* for better UX.

5. **Optimization & UI Enhancements** 
   - Cached the *Whisper model* with @st.cache_resource to *avoid reloading*.  
   - Used *Streamlit’s tab feature* to separate *Text & Audio processing*.  
   - Provided *real-time visualization* for prediction probabilities.  

This approach ensures *efficiency, usability, and real-time processing* for both text and speech-based emotion detection!
**output**
![WhatsApp Image 2025-03-12 at 15 50 12_bfac9265](https://github.com/user-attachments/assets/49353e40-f21d-4998-938a-5e97ec157cb3)
![WhatsApp Image 2025-03-12 at 15 50 33_0af56e89](https://github.com/user-attachments/assets/21659fc2-366a-4710-b920-c93ddd152bbe)
![WhatsApp Image 2025-03-12 at 15 52 02_341298e5](https://github.com/user-attachments/assets/ba6ec4b3-a4ee-402f-9c03-28e5f4aeafeb)

**Links**
**https://cyfuture.onrender.com**
