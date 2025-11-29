Chat message → AI Agent reply

Create workflow — Click + New, name it AI Chat Agent.

Add Trigger — Add When chat message received node.

Add AI Agent node — Drag and place AI Agent onto the canvas.

Connect nodes — Connect Chat Message Trigger → AI Agent.

Add Chat Model — Click the Chat Model port on AI Agent → select Google Gemini Chat Model.

Configure Model — Choose model version (e.g., Gemini 1.5 Flash/Pro).

Set AI Instructions — In AI Agent, add your System Prompt / Instructions.

(Optional) Add Memory — Click Memory and add storage if you want the bot to remember context.

(Optional) Add Tools — Add actions the AI can perform (Google Search, Email, etc.).

Configure Output — Set reply to send back to chat.

Save workflow — Click Save.

Run / Test — Send a chat message → AI Agent uses Gemini model and replies automatically.
