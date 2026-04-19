
🤖 NEO Core System

NEO is the core experimental AI engine of MDFJ.
It is designed to be lightweight, modular, and extensible.

---

📌 Purpose

The ".neo/" folder contains the internal logic of the NEO system, including:

- Intent detection 🧠
- Response engine 💬
- Language handling 🌍
- Basic tools (math, check, etc.) ⚙️
- JSON-based output format 📦

---

🧠 Philosophy

NEO is not a full AI model.
It is a foundation system designed to evolve into more advanced versions over time.

- Simple first
- Modular design
- Fully extensible
- Open-source ready (MIT license)

---

📂 Structure

.neo/
├── core/
│   ├── engine.py
│   ├── intents.json
│   ├── responses.json
│
├── lang/
│   ├── en.json
│   ├── es.json
│
├── tools/
│   ├── math.py
│   ├── check.py
│
├── config.json
└── README.md

---

🔄 How it works

1. User input is received
2. NEO detects intent (e.g. greeting, question, math)
3. System selects response template
4. Output is returned in JSON format

Example output:

{
  "input": "hi",
  "intent": "greeting",
  "language": "en",
  "response": "Hello! 😄 How are you?"
}

---

💬 Supported Intents (basic)

- greeting → hi, hello, hey
- question → what, how, why
- math → calculations
- unknown → fallback response

---

⚙️ Tools System

NEO supports internal tools:

- "math()" → basic calculator
- "check()" → validation system
- "exit()" → exit tool mode

---

🌍 Language Support

Currently supported:

- English 🇺🇸
- Spanish 🇪🇸

Auto-detection enabled for future expansion.

---

🚀 Future Plans

- Machine learning integration
- Memory system 🧠
- Plugin architecture
- Connection with MDFJ Model Hub

---

📜 License

This project uses the MIT License.

You are free to:

- use it
- modify it
- distribute it

With attribution.

---

⚠️ Status

NEO is currently in early development.
Expect frequent changes and experimental features.

---

🤖 Part of MDFJ Ecosystem

NEO is a core component of the MDFJ AI ecosystem.
