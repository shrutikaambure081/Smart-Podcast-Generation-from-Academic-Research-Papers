
# 🎙️ Smart Podcast Generation from Academic Research Papers

## 📌 Overview

**Smart Podcast Generation from Academic Research Papers** is a Generative AI-based application that converts complex academic research papers into easy-to-understand podcast-style content.

Research papers often contain technical language and complex structures, making them difficult for students, researchers, and the general public to understand. This project bridges this gap by analyzing research papers and generating **Host–Expert podcast conversations, listener-friendly analogies, key takeaways, show notes, timestamps, and audio podcasts**.

## 🎯 Objectives

- Extract and analyze content from research paper PDFs.
- Identify the main problem, methodology, findings, and research gaps.
- Convert technical research content into conversational podcast scripts.
- Generate simple analogies and key takeaways.
- Generate show notes, key terms, and timestamps.
- Convert podcast scripts into downloadable audio.

## ✨ Key Features

- 📄 **PDF Research Paper Upload**
- 🔍 **Research Paper Analysis**
- 🤖 **Generative AI-based Content Generation**
- 🎙️ **Host–Expert Podcast Conversation**
- 💡 **Listener-Friendly Analogies**
- 📝 **Key Takeaways**
- 📋 **Show Notes**
- ⏱️ **Chapter-wise Timestamps**
- 🔑 **Key Terms**
- 🔊 **MP3 Audio Generation**
- 📥 **DOCX Export**

## 🔄 System Workflow

```text
Research Paper PDF
        ↓
PDF Text Extraction
        ↓
Text Preprocessing
        ↓
Research Paper Analysis
        ↓
Problem / Methodology / Findings / Research Gap
        ↓
Podcast Script Generation
        ↓
Analogies + Key Takeaways
        ↓
Show Notes + Key Terms + Timestamps
        ↓
DOCX + MP3 Podcast Output
```

## 🛠️ Technologies Used

### AI Model
- **Llama 3.3 70B**
  - Research paper analysis
  - Research gap identification
  - Podcast generation
  - Show notes generation
  - Timestamp generation

### Tools & Technologies
- **Python**
- **Streamlit**
- **PyPDF / PyPDF2**
- **Groq API**
- **gTTS (Google Text-to-Speech)**
- **python-docx**

## 📚 Dataset

### Scientific Lay Summarisation Dataset

The project uses the **Scientific Lay Summarisation Dataset**, which contains **24,000+ scientific articles** with human-written lay summaries.

The dataset helps in:

- Converting technical content into simpler language.
- Improving readability.
- Generating listener-friendly explanations.

## 🏗️ Architecture

The application consists of the following major modules:

1. **Frontend Module**
   - Streamlit-based interactive interface.
   - Research paper PDF upload.
   - Podcast style selection.
   - Display of generated results.

2. **PDF Processing Module**
   - Extracts text from uploaded research papers using PyPDF/PyPDF2.
   - Cleans and prepares the extracted content.

3. **AI Analysis Module**
   - Uses Groq API with Llama 3.3 70B.
   - Identifies important research concepts and research gaps.

4. **Podcast Generation Module**
   - Generates a structured Host–Expert conversation.
   - Creates analogies and key takeaways.

5. **Show Notes & Timestamp Module**
   - Generates show notes, key terms, and chapter-wise timestamps.

6. **Audio & Export Module**
   - Uses gTTS to generate MP3 audio.
   - Uses python-docx to generate downloadable DOCX files.

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/smart-podcast-generation.git
cd smart-podcast-generation
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure API Key

Create a `.env` file and add your Groq API key:

```text
GROQ_API_KEY=your_api_key_here
```

**Do not upload your API key or `.env` file to GitHub.**

### 4. Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

## 📥 Input

The system accepts:

- Academic research papers in **PDF format**.

## 📤 Outputs

The system generates:

- 📄 Research paper analysis
- 🔍 Research gaps
- 🎙️ Podcast-style Host–Expert script
- 💡 Listener-friendly analogies
- 📝 Key takeaways
- 📋 Show notes
- 🔑 Key terms
- ⏱️ Timestamps
- 📄 Downloadable DOCX
- 🔊 MP3 audio podcast

## 📊 Results

The system successfully:

- Extracts and analyzes research paper content.
- Identifies the problem statement, methodology, findings, and research gaps.
- Generates podcast-style conversational scripts.
- Creates analogies and key takeaways.
- Generates show notes and chapter-wise timestamps.
- Produces downloadable DOCX and MP3 outputs.

## 🔮 Future Scope

- 🌐 Support for multiple languages.
- 🎧 More natural AI voice generation.
- 🗣️ Voice cloning.
- 📱 Mobile application development.
- 🎵 Integration with podcast platforms such as Spotify.
- 📊 Improved analysis of research figures, tables, and charts.
- 👤 Personalized podcast generation based on user preferences.

## 👥 Team

**Team No: 06**

- Priyanka Badiger
- Aishwarya Talikoti
- Preeti Chalawadi
- Shrutika Ambure

### Guided By

**Asst. Professor GuruPrasad**

**KLE Technological University**
