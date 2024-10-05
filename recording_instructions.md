# When I record a voice bank audio files, how long should be each file? How many phrases should I record in each *.wav file?

**Guidelines for Recording Voice Bank Audio Files**

When creating a voice bank for synthetic voice generation, it's important to structure your recordings effectively to ensure the best possible outcome. Here are some recommendations on the length and organization of your audio files:

---

### **1. Number of Phrases per Audio File**

- **One Phrase per Audio File**: It's standard practice to record **one phrase or sentence per `.wav` file**. This approach simplifies the alignment process between the audio and the corresponding text, which is crucial for training text-to-speech (TTS) models.

### **2. Length of Each Audio File**

- **Duration**: Each audio file should contain the full phrase or sentence, typically ranging from a few seconds up to about **10 seconds** in length.
- **Consistency**: Aim for phrases of similar length to maintain uniformity across your dataset, but natural variations are acceptable.

---

### **3. File Naming Conventions**

- **Consistent Naming**: Use a clear and consistent naming system that pairs each audio file with its text transcript.
  - **Example**: Name your files sequentially like `sentence_001.wav`, `sentence_002.wav`, etc.
- **Metadata**: Maintain a metadata file (e.g., `metadata.txt`) that lists each filename alongside its corresponding text.

### **4. Recording Quality**

- **Microphone**: Use a high-quality microphone to capture clear audio.
- **Environment**: Record in a quiet, echo-free space to minimize background noise and reverberation.
- **Microphone Placement**: Keep a consistent distance from the microphone throughout all recordings.
- **Audio Settings**:
  - **Sample Rate**: 44.1 kHz or 48 kHz is recommended.
  - **Bit Depth**: Use 16-bit or 24-bit depth.
  - **Channels**: Record in mono unless stereo is specifically required.

### **5. Speaking Style**

- **Clarity**: Speak clearly and enunciate each word without over-articulating.
- **Pace**: Maintain a natural and consistent speaking pace.
- **Tone**: Use a neutral tone unless specific emotional expressions are needed.
- **Consistency**: Try to keep your voice consistent across all recordings in terms of volume, pitch, and energy.

---

### **6. Total Recording Time**

- **Dataset Size**: For effective voice synthesis, aim to record at least **1 to 2 hours** of speech. Larger datasets (up to **5 hours or more**) can result in higher quality synthetic voices.
- **Sessions**: Break your recording sessions into manageable lengths (e.g., 30-60 minutes) to prevent vocal strain and maintain consistency.

### **7. Script Preparation**

- **Variety**: Include a diverse range of sentences that cover all phonetic combinations and prosodic patterns of the language.
- **Transcriptions**: Ensure that the text transcripts exactly match the spoken audio.
- **Punctuation**: Use proper punctuation to aid in natural speech patterns during recording.

### **8. Alignment and Editing**

- **Silence Trimming**: Leave a short silence (about 0.5 seconds) at the beginning and end of each recording.
- **Quality Check**: Listen to each recording to ensure there are no mistakes, noises, or distortions.
- **No Compression**: Save the audio files in an uncompressed format (e.g., WAV) to preserve quality.

---

### **9. Additional Tips**

- **Consistency is Key**: The more consistent your recordings are, the better the synthesized voice will perform.
- **Avoid Vocal Strain**: Stay hydrated and take regular breaks to keep your voice in good condition.
- **Warm-Up**: Do vocal warm-up exercises before recording sessions to improve clarity and reduce the risk of strain.

### **10. Software Specifications**

- **Check Requirements**: Different TTS systems may have specific requirements for audio files. Always check the documentation of the software or service you intend to use for any particular specifications.

---

By following these guidelines, you'll create a high-quality voice bank that's well-suited for training a synthetic voice model. Proper organization and consistency in your recordings will significantly enhance the performance and naturalness of the synthesized speech.

If you have further questions or need assistance with the recording process, feel free to ask!
