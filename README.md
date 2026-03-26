# Rating-Feedback-Processing-Workflow
## 🎬 Rating & Feedback Processing Workflow

This workflow automates the process of collecting user ratings, updating records, and generating intelligent responses using an AI agent.

---

### ⚙️ Workflow Overview

```mermaid
graph TD
A[Form Submission] --> B[Create Record]
B --> C{Switch: Role/Type}
C -->|Video Editor| D[Update Video Editor Rating]
C -->|Graphic Designer| E[Update Graphic Designer Rating]
C -->|Other| F[Update General Rating]
D --> G[AI Agent]
E --> G
F --> G
G --> H[Update Record with AI Output]

<img width="1095" height="472" alt="image" src="https://github.com/user-attachments/assets/68e01043-a1bd-499a-b3fc-94c2854bc34e" />
<img width="531" height="507" alt="image" src="https://github.com/user-attachments/assets/4f61e8df-3261-481a-be2e-7422793c2015" />
