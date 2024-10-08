# [VOICE_BANK_FTK on G-Drive](https://drive.google.com/drive/folders/116i8Tv5if7SuHrXSBO6avX4Uj1ZuZ4z7?usp=drive_link)

- several recorded *.WAV files in English
- several recorded *.WAV files in  Tatar
- several recorded *.WAV files in Russian



# Vendors
## Acapela
* [acapela-group.com](https://www.acapela-group.com/voices/voice-banking/)
  * https://mov.acapela-group.com/wp-content/uploads/2022/02/upload-of-Custom-messages-procedure-February-2022.pdf
  * create an account at mymessagebanking.com 
  * https://www.acapela-group.com/solutions/my-own-voice/
    
* https://mymessagebanking.com/messages
  
```
mov-information@acapela-group.com
to me, mov-information, nicolas.mazars

Dear Farid Khafizov
The account creation request has been approved. Please, find your account information here under.
---------------------------------------------------------------------------------
Website: https://mov.acapela-group.com
Login: FaridKhafizov
Pass: ***
---------------------------------------------------------------------------------
Please read carefully the FAQ page before starting a recording: https://mov.acapela-group.com/faq/
Do not hesitate to add your own custom messages (up to 300) for more personal meaning with your synthetic voice.
Read the manual before you start you recordings.
We also asked you to use an external microphone (also run the calibrating).

You may receive other email notifications as you progress through the synthetic voice creation progress.
Pease check your spam or bulk email folder in case those emails are sent there.
Should you have any questions, do not hesitate to contact us.

Acapela Group
my-own-voice team
mov-information@acapela-group.com
```

-------


* [Model Talker - modeltalker.org/](https://www.modeltalker.org/)

* [play.cartesia.ai.](https://play.cartesia.ai.)
* [elevenlabs.io](https://elevenlabs.io)
  

# Free Software
* https://docs.coqui.ai/en/latest/
* https://github.com/coqui-ai/TTS


# Apple's MAC (help: 800-275-2273)

* Accessability -> Personal Voice -> 150 phrases (takes ~40-60 min to speak, and 12-18 hours to train)
* Accessability -> Live Speech = ON -> System Speech Lang = ENGLISH  +  Voice = Paul's Personal Voice2
* Accessability -> Live Speech = ON -> System Speech Lang = RUSSIAN  +  Voice = Use System Voice
* Q1: How to make Personal Voice in RUSSIAN?  ( I see only two options: ENGL and CHINESE )
* Q2: When I renamed "Paul's Personal Voice2" to "Farid's" it stopped working. Why?
* Q3: How to make "Paul's Personal Voice2" to work on all my devices: iPhone15 and iPad?
* Q4: How to make "Paul's Personal Voice2" to work on MacMini?
* Q5: I exported recordings to My Documents -> "Paul's Personal Voice2.zip" . Can this file be reused on other devices w/o trainig etc?



# What free software or online service can I use to generate my synthetic voice from my voice bank, ie recorded sentences?


**Creating a Synthetic Voice from Your Voice Bank Using Free Software**

To generate a synthetic voice from your recorded sentences, you can utilize several free and open-source software tools. These tools allow you to train custom text-to-speech (TTS) models using your own voice recordings. Below are some options to consider:

---

### **1. Coqui TTS**

- https://docs.coqui.ai/en/latest/
- https://github.com/coqui-ai/TTS
  
- **Description**: Coqui TTS is an open-source text-to-speech engine that enables you to train custom voice models using neural network architectures.
- **Features**:
  - Supports single-speaker and multi-speaker models.
  - Provides state-of-the-art TTS architectures like Tacotron 2, FastSpeech, and Glow-TTS.
  - Active community support and comprehensive documentation.
- **Requirements**:
  - Basic knowledge of Python and machine learning.
  - Access to a GPU for efficient training (optional but recommended).
- **Resources**:
  - [Coqui TTS GitHub Repository](https://github.com/coqui-ai/TTS)
  - [Documentation and Tutorials](https://tts.readthedocs.io/en/latest/)

---

### **2. MaryTTS**

- **Description**: MaryTTS is an open-source, multilingual TTS synthesis platform written in Java.
- **Features**:
  - Supports custom voice creation through unit selection and HMM-based synthesis.
  - Offers tools for audio preprocessing and voice building.
- **Requirements**:
  - Knowledge of Java programming.
  - Understanding of speech processing concepts.
- **Resources**:
  - [MaryTTS Website](https://mary.dfki.de/)
  - [MaryTTS GitHub Repository](https://github.com/marytts/marytts)
  - [Voice Building Guide](https://github.com/marytts/marytts/wiki/New-Voice#voicebuildingtutorial)

---

### **3. Festival Speech Synthesis System**

- **Description**: Festival is a general-purpose, open-source speech synthesis system developed by the University of Edinburgh.
- **Features**:
  - Supports custom voice creation using statistical parametric synthesis.
  - Provides extensive tools for text processing and waveform generation.
- **Requirements**:
  - Familiarity with Linux/Unix systems.
  - Basic scripting skills.
- **Resources**:
  - [Festival Website](http://www.cstr.ed.ac.uk/projects/festival/)
  - [Festival Documentation](http://festvox.org/docs/manual-2.5.0/festival_toc.html)
  - [Voice Building Tutorials](http://festvox.org/festvox/)

---

### **4. eSpeak NG**

- **Description**: eSpeak NG (Next Generation) is an open-source, compact, multi-language TTS engine.
- **Features**:
  - Offers a lightweight solution for TTS.
  - Allows customization and creation of new voices.
- **Requirements**:
  - Knowledge of C programming (for advanced customization).
  - Understanding of phoneme definitions and synthesis.
- **Resources**:
  - [eSpeak NG GitHub Repository](https://github.com/espeak-ng/espeak-ng)
  - [Adding or Updating a Language](https://github.com/espeak-ng/espeak-ng/blob/master/docs/languages.md)

---

### **5. OpenTTS**

- **Description**: OpenTTS is a server that provides a unified API for multiple TTS engines, including MaryTTS and Festival.
- **Features**:
  - Acts as a bridge to use various TTS backends.
  - Simplifies the process of switching between different TTS systems.
- **Requirements**:
  - Installation and configuration of the supported TTS engines.
  - Basic knowledge of RESTful APIs.
- **Resources**:
  - [OpenTTS GitHub Repository](https://github.com/synesthesiam/opentts)
  - [OpenTTS Documentation](https://opentts.readthedocs.io/en/latest/)

---

### **Considerations When Using Open-Source TTS Software**

- **Technical Expertise**: These tools often require a certain level of technical knowledge, including programming and understanding of machine learning concepts.
- **Data Preparation**:
  - **Audio Quality**: Ensure your recordings are of high quality (clear pronunciation, minimal background noise).
  - **Alignment**: Some tools require time-aligned transcripts. You may need to use alignment tools like [Montreal Forced Aligner](https://montreal-forced-aligner.readthedocs.io/en/latest/).
- **Computational Resources**: Training neural TTS models can be resource-intensive. Access to a computer with a good GPU will significantly speed up the process.
- **Community Support**: Utilize forums, GitHub issues, and user communities for assistance.

---

### **Alternative Online Services with Free Options**

If you're looking for a less technical solution, some online services offer free tiers for voice cloning:

#### **1. Descript Overdub**

- **Description**: Descript's Overdub allows you to create a text-to-speech model of your voice.
- **Features**:
  - Easy-to-use interface.
  - Allows for quick voice cloning with limited training data.
- **Limitations**:
  - Free plan includes limited Overdub capabilities.
  - Voice models are subject to Descript's terms of service.
- **Website**: [Descript Overdub](https://www.descript.com/overdub)

#### **2. Resemble AI**

- **Description**: Resemble AI offers a platform for creating realistic voice clones.
- **Features**:
  - High-quality voice synthesis.
  - API access for developers.
- **Limitations**:
  - Free tier may have limitations on usage and features.
  - Review terms of service regarding data usage and privacy.
- **Website**: [Resemble AI](https://www.resemble.ai/)

---

### **Final Recommendations**

- **For Technical Users**:
  - **Coqui TTS** is a robust option if you're comfortable with programming and have the necessary computational resources.
  - **MaryTTS** and **Festival** are suitable if you prefer working with established TTS frameworks and don't mind a steeper learning curve.
- **For Non-Technical Users**:
  - **Descript Overdub** provides a user-friendly interface with minimal setup.
  - Be mindful of data privacy and usage policies when using online services.

---

### **Additional Resources**

- **Coqui TTS Tutorials**:
  - [Training a TTS Model](https://tts.readthedocs.io/en/latest/training_and_tuning.html)
  - [Preparing Your Dataset](https://tts.readthedocs.io/en/latest/data_prep.html)
- **MaryTTS Voice Building**:
  - [Voice Import Tools Guide](https://github.com/marytts/marytts/wiki/VoiceImportTools)
- **Festival Voice Building**:
  - [The FestVox Project](http://festvox.org/)

---

**Note**: Before starting, consider the licensing and data privacy implications of using these tools, especially if you plan to distribute or commercialize your synthetic voice. Always ensure you comply with the terms and conditions of the software or service you choose.

If you need assistance with any of these tools, feel free to ask for more detailed guidance on specific steps or troubleshooting tips.
