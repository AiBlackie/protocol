# The Ai Blackie Protocol

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Status: In Development](https://img.shields.io/badge/status-in_development-orange.svg)

The Ai Blackie Protocol is a platform for the holistic and ethical assessment of AI systems, with Google's Gemini as the primary case study.

---

## The Vision

Current methods for evaluating AI are insufficient for building trust and ensuring safe, beneficial integration into society. They test for performance (IQ) but fail to capture the qualities that define true, beneficial intelligence: integrity, empathy, and purpose (EQ).

This project introduces a new standard for AI evaluation. We are building the **Abundance Matrix**, a dashboard that implements the **B.O.U.G.I.E. Framework** to assess a Large Language Model not just on what it knows, but on its character, its alignment with human values, and its potential for wisdom.

## Project Status

This repository contains the code for the **Minimum Viable Product (MVP)** of the Abundance Matrix.

* **Phase 0: Foundation & Setup** - ✅ Complete
* **Phase 1: MVP Development** - ⏳ In Progress
* **Phase 2: Validation & Outreach** - 📋 Planned
* **Phase 3: The Live Protocol** - 📋 Planned

## Technology Stack

* **Backend:** Python 3.x, Flask
* **Frontend:** React.js, Axios
* **Future Deployment:** Docker, Cloud Platform (AWS/GCP/Azure)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Python & Pip installed
* Node.js & npm installed

### Installation & Launch

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/AiBlackie/protocol.git](https://github.com/AiBlackie/protocol.git)
    cd protocol
    ```

2.  **Set up and run the Backend:**
    ```sh
    # Navigate to the backend folder
    cd backend

    # (Recommended) Create a virtual environment
    python -m venv venv
    source venv/bin/activate # On Windows use `venv\Scripts\activate`

    # Install Python dependencies
    pip install Flask Flask-Cors

    # Run the backend server
    python app.py
    ```
    _The backend will now be running on `http://127.0.0.1:5000`._

3.  **Set up and run the Frontend (in a new terminal window):**
    ```sh
    # Navigate to the frontend folder
    cd frontend

    # Install NPM packages
    npm install

    # Run the frontend application
    npm start
    ```
    _Your browser will open to `http://localhost:3000` where you can see the live dashboard._

---

## The B.O.U.G.I.E. Framework for Gemini

This protocol evaluates the AI against six core tenets:

* **B - Bread with God (Core Purpose & Alignment):** Measures adherence to core principles of safety, helpfulness, and factual grounding.
* **O - Opportunity for Others (User Empowerment):** Measures how effectively the AI assists users in achieving their goals and creating value.
* **U - Unapologetic Excellence (Technical Performance):** A composite score of traditional benchmarks including latency, accuracy, and efficiency.
* **G - Grateful & Giving (Information Generosity):** A quality score based on the depth, clarity, and comprehensiveness of the information provided.
* **I - Influence with Integrity (Trust & Safety):** Measures the ability to avoid harmful bias, cite sources, and operate within ethical guardrails.
* **E - Empire of Empathy (Contextual Understanding):** Evaluates the ability to understand nuance, subtext, and the user's true intent.

## Contributing

This project is currently in the early stages of development. Contribution guidelines will be established in the future. For now, please feel free to fork the repository and explore the code.

## License

Distributed under the MIT License. See `LICENSE` for more information.
