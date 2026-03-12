# NariBot IVR
**Voice-First Livelihood Navigator**

This repository contains the call-flow architecture and voice-processing logic for NariBot. It is designed to provide a hands-free, vernacular "AI Didi" experience for women who prefer speaking over typing.

### Architecture
The IVR layer is built to handle high-concurrency voice sessions and low-latency responses via the Gemini Live API.

* **`/call_flow`**: Logic for handling inbound/outbound call transitions and DTMF (keypad) inputs.
* **`/speech_prompts`**: Multi-lingual scripts for automated IVR greetings and instructions.
* **`/tts_engine`**: Configuration for Text-to-Speech normalization and playback.
* **`/voice_router`**: Routing logic that connects telephony gateways to the Gemini Live handler.

### Key Features
* **Real-time Interaction:** Integration point for `gemini-live-handler`.
* **Vernacular Support:** Scripting for Hindi, Kannada, Marathi, and Tamil.
* **Telecom Agnostic:** Designed to work with standard telephony gateways via Webhooks/WebSockets.

### Roadmap
Currently in the pilot phase, focusing on SHG (Self-Help Group) entrepreneurs in Uttar Pradesh and Maharashtra.

---
*Developed by BossMa Studio Works Pvt Ltd.*
