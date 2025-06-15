# 📞 Twilio + ElevenLabs Voice Streaming Server

A Fastify server that integrates **Twilio Programmable Voice** with **ElevenLabs Conversational AI**, enabling real-time, bidirectional voice interactions via WebSockets.

---

## 🚀 Features

- Initiates outbound phone calls using Twilio
- Streams audio to/from ElevenLabs Conversational AI
- Uses WebSockets for low-latency audio transmission
- Supports custom user metadata for personalized conversations
- Includes REST endpoints and TwiML webhook handling

---

## 🧰 Tech Stack

- [Fastify](https://www.fastify.io/)
- [Twilio Voice API](https://www.twilio.com/docs/voice)
- [ElevenLabs Conversational AI](https://docs.elevenlabs.io/)
- [WebSocket](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)
- [dotenv](https://www.npmjs.com/package/dotenv)

---

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

2. **Install dependencies:
```bash

npm install
```
3. Create a .env file with the following content:

```bash

PORT=8080

TWILIO_ACCOUNT_SID=your_twilio_account_sid
TWILIO_AUTH_TOKEN=your_twilio_auth_token
TWILIO_PHONE_NUMBER=your_twilio_phone_number

ELEVENLABS_API_KEY=your_elevenlabs_api_key
ELEVENLABS_AGENT_ID=your_elevenlabs_agent_id

```




