
## FOS (Focus on Speaking): An AI-Powered Real-Time Presentation & Meeting Assistant for Enhanced Clarity and Intelligent Visualization
<img width="1230" alt="FOS intro" src="https://github.com/user-attachments/assets/d9f63c92-d7d7-493d-b77c-d8c98f310c1f" />

### 25-2 Hanyang University Software Engineering Project

FoS is an LG display–linked real-time meeting AI prompter that transforms a traditional teleprompter into an active, context-aware assistant. It supports the entire lifecycle of presentations and meetings – before, during, and after – by listening to speech, understanding context, and surfacing the next required information on LG displays and personal dashboards.

---

## 💡 Proposal

We introduce **FoS (Focus on Speaking)**, a real-time AI meeting prompter designed to reduce cognitive overload during presentations and discussions.  
Modern speakers must manage speech delivery, scripts, slide transitions, time, and audience reactions simultaneously, while participants struggle to track ideas, decisions, and follow-up tasks. This often leads to **omitted content, topic drift, unclear decisions, and reduced meeting efficiency.**

FoS addresses these issues by integrating **real-time STT, semantic speech–script alignment (KoSentence-BERT + LLM), dual-screen teleprompter architecture, and a structured meeting-intelligence system.**

When key content is skipped, FoS detects omissions, suggests natural bridging sentences, and automatically highlights the correct script segment. Meanwhile, the shared LG display visualizes the **agenda map, decisions, action items, and fact-checks**, while the presenter sees a private dashboard of pace, progress, and AI suggestions.

From an organizational perspective, FoS converts raw speech into **structured, reusable meeting knowledge**. Utterances are tagged by intent (idea, decision, action item, question), organized into a real-time agenda graph, and exported as a **Meeting Summary Report**.  
This enhances documentation quality, meeting recall, and long-term decision tracking.

By integrating tightly with **LG Smart Office (webOS, One:Quick, signage)** and cloud AI services, FoS provides a practical, extensible platform for more focused presentations and smarter meetings.

---

## 🔑 Key Features

- Real-time STT and speech–script synchronization  
- Keyword omission detection + real-time script reconstruction  
- Dual-screen architecture (Presenter Dashboard + LG Shared Display)  
- Real-time agenda map & intent tagging  
- Decision / Action Item widget  
- Fact-check widget (RAG + web search)  
- Automatic Meeting Summary Report  

---

## 🏗 Architecture Design
<img width="2880" alt="SWarchitecture" src="https://github.com/user-attachments/assets/26e4a3ec-a780-4ed7-b1c6-062eef7cf28c" />

---

## 👥 Team Potato Savior

| Name          | Department / Division                   | Role                       | Location                 | Email                     |
|---------------|------------------------------------------|-----------------------------|---------------------------|----------------------------|
| Sangyoon Kwon | Department of Computer Science           | Backend Development         | Seoul, Republic of Korea | is0110@hanyang.ac.kr      |
| Hyeyun Kwon   | Department of Information Systems        | Frontend Development        | Seoul, Republic of Korea | herakwon1124@hanyang.ac.kr |
| Dohoon Kim    | Department of Computer Science           | Backend Development         | Seoul, Republic of Korea | april2901@hanyang.ac.kr   |
| Seohyun Kim   | Department of Information Systems        | Frontend Development        | Seoul, Republic of Korea | dianwls0326@hanyang.ac.kr |
| Daeun Lee     | Division of Business Administration      | UI Design, PM, User Testing | Seoul, Republic of Korea | shinran2929@hanyang.ac.kr |
| Minhyuk Jang  | Division of Business Administration      | UI Design, PM, User Testing | Seoul, Republic of Korea | jmh12230@hanyang.ac.kr    |

