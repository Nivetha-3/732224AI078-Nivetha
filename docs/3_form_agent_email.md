Form submission → AI Agent processes → Gmail sends email

Create workflow — Click + New, name it Form Agent Email.

Add Form Trigger — Add On form submission node (select your form).

Add AI Agent — Place AI Agent node on the canvas.

Connect nodes — Connect Form Submission → AI Agent.

Add Chat Model — Click Chat Model on AI Agent → choose Google Gemini Chat Model.

Configure Model — Select the Gemini version and set the system prompt/instructions.

Map form data — In the AI Agent, map the user’s form fields to the inputs.

(Optional) Add Memory — If needed, add Memory for context history.

(Optional) Add Tool — Add tools for actions (search, calculations, etc.).

Add Gmail node — Add Send a message (Gmail).

Connect AI Agent → Gmail — Drag connection.

Configure Gmail — Fill To, Subject, Body.
Use AI Agent output inside the email body.

Save workflow — Click Save.

Test workflow — Submit form → AI Agent processes → Gmail sends email automatically.
