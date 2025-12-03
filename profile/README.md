## FOS (Focus on Speaking)
<img width="1230" height="694" alt="FOS intro" src="https://github.com/user-attachments/assets/d9f63c92-d7d7-493d-b77c-d8c98f310c1f" />
Team Potato Savior

FoS is an LG display–linked real-time meeting AI prompter that extends a traditional teleprompter into an active, context-aware assistant.  
It supports the entire lifecycle of presentations and meetings – before, during, and after – by listening to speech, understanding context, and surfacing the next required information on LG displays and personal dashboards.

### Proposal

We introduce FoS (Focus on Speaking), a real-time AI meeting prompter that extends a traditional teleprompter into an active, context-aware assistant. In modern presentations and meetings, speakers must simultaneously manage speech delivery, script reference, slide transitions, time constraints, and audience reactions. Participants, meanwhile, struggle to follow complex discussion flows and remember key decisions. This cognitive overload often leads to omitted content, topic drift, and ambiguous outcomes, reducing both presentation quality and meeting efficiency.

FoS addresses these challenges by linking an AI-driven teleprompter with LG displays and a dual-screen architecture. The system continuously listens to meeting audio, performs real-time STT, and semantically aligns speech with the prepared script using KoSentence-BERT and LLMs. When important content is skipped, FoS detects omissions, proposes natural bridging sentences, and automatically highlights the next relevant part of the script. At the same time, it visualizes an agenda map, decisions, and action items on a shared display while providing a private coaching dashboard for the presenter that shows pace, progress, and AI suggestions without distracting the audience.

From an organizational perspective, FoS transforms raw meeting speech into structured, reusable knowledge. Utterances are tagged by intent (idea, decision, action item, question, fact-check request), aggregated into an agenda network, and summarized into a Meeting Summary Report containing topics, decisions, follow-up tasks, and referenced evidence. This persistent data layer not only improves documentation quality but also enables analysis of meeting efficiency and decision-making patterns over time. By integrating seamlessly with LG’s smart office ecosystem and cloud-based AI services, FoS offers a practical, extensible platform for more focused presentations and smarter, outcome-driven meetings.

### Key ideas:

- Real-time STT and script–speech synchronization
- Keyword omission detection and real-time script reconstruction
- Dual-screen architecture (Presenter Dashboard + Shared Meeting Board on LG displays)
- Agenda map, decision/action-item widget, and fact-check widget
- Automatic Meeting Summary Report after each session

### Architecture Design
<img width="2880" height="1524" alt="SWarchitecture" src="https://github.com/user-attachments/assets/26e4a3ec-a780-4ed7-b1c6-062eef7cf28c" />

### [Potato Savoir] Members

| Name          | Department / Division                   | Role                       | Location                 | Email                     |
|---------------|------------------------------------------|-----------------------------|---------------------------|----------------------------|
| Sangyoon Kwon | Department of Computer Science           | Backend Development         | Seoul, Republic of Korea | is0110@hanyang.ac.kr      |
| Hyeyun Kwon   | Department of Information Systems        | Frontend Development        | Seoul, Republic of Korea | herakwon1124@hanyang.ac.kr|
| Dohoon Kim    | Department of Computer Science           | Backend Development         | Seoul, Republic of Korea | april2901@hanyang.ac.kr   |
| Seohyun Kim   | Department of Information Systems        | Frontend Development        | Seoul, Republic of Korea | dianwls0326@hanyang.ac.kr |
| Daeun Lee     | Division of Business Administration      | UI Design, PM, User Testing | Seoul, Republic of Korea | shinran2929@hanyang.ac.kr |
| Minhyuk Jang  | Division of Business Administration      | UI Design, PM, User Testing | Seoul, Republic of Korea | jmh12230@hanyang.ac.kr    |
