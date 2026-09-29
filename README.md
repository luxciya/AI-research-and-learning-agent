# 🤖 AI Research & Learning Agent

An AI-powered research and learning workflow that takes a topic and time period, gathers relevant information, creates a simplified summary, converts the result into audio, and sends the generated audio through email.

The project was inspired by AI agent workflows and learning/research automation.

## 📌 Problem

When learning a new topic, collecting information from multiple sources, summarizing it, and converting it into a useful learning format can take time.

This project automates several of these steps using an AI-powered workflow.

## 💡 What I Built

I created an **AI Research & Learning Agent** using n8n and Gemini.

The workflow can:

* Accept a research topic
* Use a specified time period
* Search for relevant information
* Process and summarize the information
* Generate learning-friendly content
* Convert the generated text into audio
* Send the audio through Gmail

## 🏗️ Workflow

```text
Topic + Time Period
        ↓
      Gemini
        ↓
    Web Search
        ↓
Research & Information Processing
        ↓
   AI Summary
        ↓
  ElevenLabs TTS
        ↓
    Audio File
        ↓
      Gmail
        ↓
   User Receives Audio
```

## 🧩 Main Components

The project was designed around several AI-agent components:

* **Models** – Gemini
* **Tools** – Web search
* **Knowledge Management** – Research information and generated content
* **Audio Speech** – ElevenLabs
* **Communication** – Gmail
* **Workflow Automation** – n8n

The current version focuses on the core workflow rather than implementing every possible AI-agent component.

## 🛠️ Technologies Used

* **n8n**
* **Google Gemini**
* **Web Search**
* **ElevenLabs**
* **Gmail**
* **AI Agents / LLM**
* **Workflow Automation**

## 🎯 My Role

I worked on:

* Designing the workflow
* Creating the n8n automation
* Configuring Gemini
* Connecting search functionality
* Designing the research and summarization flow
* Integrating ElevenLabs for text-to-speech
* Connecting Gmail for audio delivery
* Testing and debugging the workflow

## 📁 Repository Contents

```text
ai-research-learning-agent/
│
├── README.md
├── workflow.json
```

### `workflow.json`

The exported n8n workflow can be imported into another n8n environment.

> Credentials and API keys are not included in the workflow repository.

## 🚀 How to Use

### 1. Import the workflow

Open your n8n instance and import:

```text
workflow.json
```

### 2. Configure credentials

Connect your own:

* Gemini API
* Search tool/API
* ElevenLabs
* Gmail

Never publish API keys or private credentials on GitHub.

### 3. Provide a topic

Enter a topic and the required time period.

### 4. Run the workflow

The workflow researches the topic, generates a summary, converts it into audio, and sends the result through Gmail.

## 🎓 Example Use Cases

This workflow can be used for:

* Learning new technologies
* Researching recent developments
* Creating audio learning material
* Summarizing technical topics
* Personal research automation

## 🔮 Future Improvements

* Add stronger source verification
* Add more research tools
* Add persistent memory
* Add additional output formats
* Add Telegram delivery
* Add more advanced agent orchestration
* Add guardrails for generated content

## 👩‍💻 Project

**AI Research & Learning Agent**

Built as a practical AI automation project using n8n, Gemini, ElevenLabs, and Gmail.
