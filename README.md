<div align="center">
    
# 👋 Hi Everyone! 👋 I'm Kyungseok Lee. <br/> I'm a dreamer of studying HCI & VR/AR/MR.

![header](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&fontColor=d6ace6&animation=blink&height=300&section=header&text=I'm&nbsp;Matthew&fontSize=30)

## Life is like riding a bicycle. To keep your balance, you must keep moving. -Albert Einstein-

I'm a **Mechanical Engineering** student at **Hanyang University** who making things I imagine into reality and new technologies.

By day, I'm an engineer-in-training, learning the principles of how the world works. By night, I'm a **CEO and Founder**, turning bold ideas into real-world businesses. I've led teams, built products from 0-to-1, and secured ₩55M in funding, all driven by a relentless 'Grit' and a passion for problem-solving.

My journey is now converging on a singular mission: to merge the physical (Mechanics) and the digital (AI) worlds. I'm pivoting my 'Founder's mindset' to become a researcher in **HCI, Computer Vision, and Robotics**.

</div>

## 📫Contact
[![Gmail Badge](https://img.shields.io/badge/-bu5119@hanyang.ac.kr-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:bu5119@hanyang.ac.kr)](mailto:bu5119@hanyang.ac.kr)
[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/YOUR-LINK-HERE)](https://www.linkedin.com/in/voraleo/)

<br>

---

## 🛠️ I'm a Full-stack Maker

I thrive on bridging the entire creation process, from a rough idea to a physical, working prototype.

* **Software:** `Python` `AI/ML` `Computer Vision` `Webpage` `JavaScript` `React` `Development` 
* **Hardware:** `Robotics (ROS2)` `Circuitry` `Hardware Prototyping`
* **Fabrication:** `3D Printing` `CATIA, SolidWorks, NX-UG etc 3D CAD` `3D Modeling` `SolidWorks CAM, NX-UG CAM, MasterCAM 3D CAM` `MCT` `CNC` 
* **Interaction:** `HCI` `Virtual Reality (VR)`

<br>

---

## 📊 My GitHub Stats

[![Kyungseok's Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=wannahappyaroundme&layout=compact&theme=radical&hide_border=true)](https://github.com/anuraghazra/github-readme-stats)

<br>

---

## 🌱 What I'm Up To

* `🔭` **I’m currently working on...**
    1.  **[Proof #1]** Building a **ROS2-based Autonomous Vehicle** from the ground up. (Completing the S/W)
    2.  **[Proof #2]** Planning my next project: using CV to turn my robot's camera into an 'eye' that can scan and map a room, inspired by the 'ParaHome' paper.

* `🌱` **I’m currently learning...**
    * **Pytorch** (The '60 Minute Blitz' official tutorial)
    * **Computer Vision** (Stanford's CS231n 2025 Spring course)
    * **Algorithms & Data Structures** ('이것이 코딩 테스트다')

* `👯` **I’m looking to collaborate on...**
    * Exciting projects involving **HCI, Robotics, VR/AR, or CV**. If you're building something cool, I'd love to hear about it!

* `💬` **Ask me about...**
    * **Entrepreneurship** (especially 0-to-1), pivoting, and problem-solving.
    * **3D Printing** and rapid hardware prototyping.
    * My 'Optimal Realism' (진인사대천명) philosophy.

* `📫` **How to reach me:**
    * `bu5119@hanyang.ac.kr`
    * `https://www.linkedin.com/in/voraleo/`

* `⚡` **Fun fact:**
    * I'm fascinated by 'Vitual Reality' and 'Superpower-Webtoon'. My ultimate goal is to build the technology that makes those sci-fi concepts a reality.

<br>

---

## 🚀 Featured Projects (My "Grit" in Action)

* **[🤖 Autonomous Vehicle (ROS2 Project)]**
    * *Comming Soon*
    * My current 'One Thing'. Building a fully functional autonomous car from H/W assembly to ROS2-based S/W implementation.

* **[📈 STLAB (AI Music Valuation)]**
    * *private*
    * **Founder & CEO.** Developed an AI (LSTM) based music valuation model. Led the team to secure ₩55M in government funding.

* **[🛰️ Abandoned Vehicle Detection (CV Project)]**
    * *https://github.com/wannahappyaroundme/satellite_vehicle_tracker*
    * A computer vision project utilizing satellite data and YOLO models to identify illegally parked vehicles.
    * 
graph TD
    %% --- 스타일 정의 ---
    classDef user fill:#e3f2fd,stroke:#1565c0,stroke-width:2px,color:#000
    classDef rust fill:#fff3e0,stroke:#ef6c00,stroke-width:3px,color:#000
    classDef ai fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px,color:#000
    classDef infra fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px,color:#000
    classDef ext fill:#ffebee,stroke:#c62828,stroke-width:2px,stroke-dasharray: 5 5,color:#000

    %% --- 1. 사용자 영역 ---
    subgraph Frontend ["🖥️ Frontend Layer"]
        User((👤 User)):::user
        UI[💬 Chat Interface]:::user
        Store[📦 State Manager]:::user
    end

    %% --- 2. 백엔드 로직 ---
    subgraph Backend ["⚙️ Backend Layer"]
        IPC((⚡ IPC Bridge)):::rust
        Orchestrator[🧠 Main Orchestrator]:::rust
        
        subgraph Caps ["✨ Capabilities"]
            RAG[📚 RAG Service]
            Persona[🎭 Persona & LoRA]
            Vision[👁️ Screen Context]
        end

        subgraph Tools ["🛠️ Tool System"]
            ToolMgr[🧰 Tool Manager]
            Logic_Web[🌐 Web Search]
            Logic_File[📂 File Ops]
            Logic_Sys[💻 System Info]
        end
    end

    %% --- 3. 인프라 영역 ---
    subgraph Infra ["🔐 Local Infrastructure"]
        Ollama[[🤖 Ollama Runtime]]:::ai
        DB[(🗄️ Encrypted DB)]:::infra
        FS[📂 Local Filesystem]:::infra
    end

    %% --- 4. 외부 영역 ---
    Internet((☁️ Internet)):::ext

    %% =================================================
    %% --- 워크플로우 연결 ---
    %% =================================================

    %% 1. 입력 및 전달
    User -->|1. 질문| UI
    UI <-->|2. 동기화| Store
    UI -->|3. 명령| IPC
    IPC -->|4. 요청| Orchestrator

    %% 2. 컨텍스트 구성
    Orchestrator -->|5. 기억 검색| RAG
    RAG -.->|쿼리| DB
    Orchestrator -->|6. 성격 로드| Persona
    Persona -.->|설정 로드| DB
    Orchestrator -->|7. 화면 캡처| Vision

    %% 3. AI 추론 및 도구 사용
    Orchestrator ==>|8. 프롬프트 전송| Ollama
    Ollama ==>|9. 판단| Orchestrator
    
    %% 도구 실행 분기 (문법 단순화)
    Orchestrator -.->|10-A. 도구 호출| ToolMgr
    ToolMgr --> Logic_Web
    ToolMgr --> Logic_File
    ToolMgr --> Logic_Sys
    
    Logic_Web -.->|접속| Internet
    Logic_File -.->|IO| FS
    ToolMgr -.->|10-B. 결과 반환| Orchestrator
    Orchestrator ==>|10-C. 결과 재전송| Ollama

    %% 4. 최종 응답 및 학습
    Ollama ==>|11. 답변 스트리밍| Orchestrator
    Orchestrator -->|12. UI 렌더링| IPC
    IPC --> UI
    
    %% 5. 백그라운드 학습
    Orchestrator -.->|13. 저장/학습| DB
