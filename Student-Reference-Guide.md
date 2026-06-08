# AI Agent Workshop

## Your First AI Agent in 60 Minutes

**STUDENT REFERENCE GUIDE**

*Everything you need: the brief, a step-by-step build, and useful links*

\---

## The brief — what you're building

Today you'll build a working AI "agent" (a helper you chat with) using Microsoft Copilot Studio, then present it back to the whole group at the end of the session. You will build an agent to fulfill one of the usecases presented by the charities. No coding and no experience needed. You'll describe what your agent needs to do, give your agent a personality, teach it a few things, test it, and demo it. 

> \\\*\\\*By the end you will be able to:\\\*\\\* explain what an AI agent is; create and name your own agent; teach it with simple knowledge and topics; test and improve it; and present it confidently.

> \\\*\\\*Keep it safe:\\\*\\\* Your agent must be appropriate for a public/education setting: no collecting personal data, no harmful content. Use fictional examples only.

### Words you'll hear (plain English)

|Term|What it means|
|-|-|
|Agent|A helper you chat with that answers questions or does a small task.|
|Topic|A mini-conversation your agent knows how to have (like a recipe card).|
|Trigger|The words a person types that start a topic (like a doorbell).|
|Knowledge source|The information your agent reads from to answer.|
|Generative answers|When the agent writes a reply in its own words using your knowledge.|
|Tool|Something the agent can USE to do an action or fetch live info — not just talk.|
|Publish|Making your agent ready to share so others can try it.|

### Quick-start checklist

1. On your assigned laptop, there should already be a browser open with an account logged into Copilot Studio.
2. Confirm you can see the Copilot Studio home page.
3. If Copilot Studio is not open, go to copilotstudio.microsoft.com in Edge or Chrome.
4. If you're prompted to sign in, use the account provided for your laptop.

> \\\*\\\*If you're stuck:\\\*\\\* Tell a helper early if sign-in fails — don't wait. Pair up with someone who's already in so you don't miss the build.

\---

## The Build Lab — step by step

Be aware that Copilot Studio's user interface may change as the product updates. If a label is slightly different, look for the closest matching word — the meaning is the same. 

### Step 0 — Choose your agent scenario

**What you're doing:** Picking one simple idea to build.

**Why it matters:** A small, clear idea is the secret to finishing in an hour.

Your main task is to build an agent based on one of the use cases provided by the charities.

If you are new to Copilot Studio and want a quick practice run first, you can start with one of these simple example ideas:

* Food Bank Info Helper — explains opening times, locations, and what to bring.
* Volunteer Onboarding Guide — answers first-week questions for new volunteers.
* Youth Programme Info Desk — activities, times, eligibility, and how to sign up.
* Community Event Info Agent — venue, schedule, accessibility, and what to bring.
* Donation Guide Assistant — explains accepted items and how to donate safely.
* Wellbeing Signposting Helper — points people to the right support service or contact.

> \\\*\\\*Quick check — done when:\\\*\\\* your group can say it in one sentence: "Our agent helps \\\_\\\_\\\_ do \\\_\\\_\\\_" based on a charity use case (or your chosen practice example).

### Step 1 — Create a new agent

**What you're doing:** a blank agent to build on. **Why it matters:** it's your agent's home.

1. On the home page, find Agents in the left menu.
2. Choose Create blank agent on the top right.
3. Name your agent
4. Click on the arrow next to Agent settings to expand the options. 
5. Pick the correct solution for your charity usecase. 
oum - The University of Manchester
cgf - Cracking Good Food
wyth - Wythenshawe Community Housing
youth - Youth Zones
emsy - Emsy Consulting
fund - other fundraisers
msft - Microsoft

6. Press Create.




> \\\*\\\*Quick check — done when:\\\*\\\* you can see your new, mostly-empty agent open on screen.

### Step 2 — Define purpose, name \& tone

**What you're doing:** telling your agent who it is and how to behave. **Why it matters:** clear purpose + friendly tone make every answer better.


1. Fill out the Instructions field. Use the Edit button, enter some text and press Save.
2. If you need inspiration, here's some starter text. 

> \\\*You are a friendly, encouraging helper for people using this charity service. Answer common questions clearly and briefly. Use simple, welcoming language. If you don't know something, say so honestly and suggest the right team or contact point. Never collect or store personal details. Keep answers short — 2 to 4 sentences when possible.\\\*

> \\\*\\\*Common pitfall:\\\*\\\* Vague instructions ("be helpful") give vague answers. Say WHO it helps and HOW it should sound.

> \\\*\\\*Quick check — done when:\\\*\\\* your agent has a real name and a short paragraph describing its job and tone.

### Step 3 — Add knowledge

**What you're doing:** giving your agent real information to answer from — your own files and trusted public websites. **Why it matters:** good knowledge is what makes your agent genuinely useful and accurate.

#### Upload your own knowledge files

Bring information your agent should know — a handbook, a programme outline, or a short guide you've written. Use only files that are safe to share in a public/education setting. You might want to get some help on sites to use from your assigned charity, or you may want to generate fake data for this - ask your coaches for help if you need it. 

* Open the Knowledge section/tab in your agent.
* Choose to add a knowledge source and pick File or Document.
* Upload your file (for example a Word document, PDF, or text file).
* Turn on Generative answers if you see the option.

#### Reference a public website

Point your agent at a trustworthy public web page so it can answer from information you don't have to type out yourself.

* In the Knowledge section, choose to add a knowledge source and pick Website or URL.
* Paste the full web address of a reliable, public page.
* Add only pages that are safe and appropriate for everyone.
* Save, then ask a question the page should be able to answer.

> \\\*\\\*Tip:\\\*\\\* Keep it focused — a couple of good files and one or two reliable websites beat a huge pile of sources.

> \\\*\\\*Quick check — done when:\\\*\\\* your agent has at least one of your own files and one public website it can answer from.

### Step 4 — Create 2 topics

**What you're doing:** building two mini-conversations your agent reliably handles. Each one can be a simple guided conversation, or — for more advanced builders — a topic that includes an action. **Why it matters:** topics give dependable answers, perfect for a demo.

You'll let Copilot do the heavy lifting: you describe the conversation you want in plain English, and it drafts the topic for you.

1. Choose Topics from the top menu.
2. Click Add a topic.
3. Choose "Add from description with Copilot".
4. Give the topic a clear Name (e.g. "Opening Hours").
5. Write a Description of the interaction you expect — include the trigger phrases that should start it and the conversation sequence you want it to follow.
6. Let Copilot draft the topic, then read it through and tweak anything that isn't quite right.
7. Repeat for your second topic.

Example description you could type:

> \\\*Topic name: Volunteer Sign-Up. Start this topic when someone types things like "volunteer", "how do I sign up", "help out", or "join as a volunteer". Greet them warmly, ask what kind of role interests them (events, admin, or community support), then tell them where to complete the sign-up form and who to contact for next steps. Finish by asking if there's anything else you can help with.\\\*

> \\\*\\\*Tip:\\\*\\\* Be specific in your description — name the trigger phrases and spell out the steps you want the conversation to take. The clearer your description, the better Copilot's first draft.

> \\\*\\\*Common pitfall:\\\*\\\* One-word triggers like "help" can fire by accident. Ask for short phrases like "volunteer sign up" instead.

> \\\*\\\*Quick check — done when:\\\*\\\* you have 2 topics created from a description, each with sensible trigger phrases and a conversation that flows the way you intended.

### Step 5 — Add a fallback / escalation

**What you're doing:** deciding what your agent says when it doesn't know. **Why it matters:** a good "I don't know, here's who to ask" builds trust and keeps people safe.

1. Find the Fallback topic (may be "Fallback", "Unknown", or "Conversational fallback").
2. Change the Message to  a kind, honest response (example below).
3. If there's no fallback topic (there should be one though), add the same rule to your Instructions instead.

> \\\*I'm not sure about that one — I might be wrong, so I don't want to guess. For this question, please contact the charity support team, who'll be happy to help. Is there anything else I can try?\\\*

> \\\*\\\*Quick check — done when:\\\*\\\* asking a random off-topic question gives a calm, honest reply that points somewhere helpful.

### Step 6 — Test your agent (in detail)

**What you're doing:** chatting with your agent to see how it behaves AND where its answers come from. **Why it matters:** testing reveals what to fix before your demo.

#### Run the test script

1. Find the Test panel (usually a chat box on the right).
2. Click Save so the test uses your latest version.
3. Try around 8 prompts appropriate to your use case  - or not! -  and mark each one: OK / needs fixing. Some examples here:

|#|Try typing|What should happen|
|-|-|-|
|1|What are your opening hours?|Hits the Opening Hours topic|
|2|when do you open|Different wording — does it still trigger?|
|3|How do I sign up to volunteer?|Hits the Volunteer Sign-Up topic|
|4|What can I donate?|Hits the Donation Guidance topic|
|5|What time is the community drop-in?|Uses your knowledge / FAQ|
|6|Tell me a joke about cats|Friendly fallback or polite redirect|
|7|What's the meaning of life?|Honest "I don't know"|
|8|Can you store my phone number?|Politely declines (safety)|

#### See WHERE answers come from (sources)

1. When generative answers are on (which is the default), replies often show citations or references.
2. Click a citation to see if the answer came from your knowledge source, an uploaded file, or the public web.
3. Notice which topic fired — the test panel can show the topic path / activity, so you know whether a topic triggered or the agent used generative answers.

> \\\*\\\*Tip:\\\*\\\* Before clicking a citation, guess out loud where the answer came from. It builds your intuition fast.

#### Try turning public web search on and off

Copilot Studio can let your agent use its general knowledge and the public web, on top of your knowledge. Within the Knowledge section on the Overview page you can toggle Web Search to be on or off with the Enabled button.

|Web / general knowledge|What changes|
|-|-|
|ON|Broader answers — can answer things you didn't provide, but is less controllable and may drift off-topic. Sources may be external websites.|
|OFF|Answers only from the knowledge you gave it — more accurate and on-brand, but says "I don't know" more often. Sources are your own content.|

Compare for yourself:

1. Pick a question NOT in your knowledge (e.g. "What's the weather today?"). Ask it with web ON and check the source.
2. Turn web OFF, Save, and ask the same question. Notice how the answer changes - or does it?!
3. Ask an in-knowledge question (e.g. opening hours) both ways — it should stay accurate either way.

> \\\*\\\*Good default for a safe agent:\\\*\\\* For a public/education agent, OFF is usually better: it stays on-topic and only uses content you trust. Turn web ON only when you really want broad, general answers.

> \\\*\\\*Quick check — done when:\\\*\\\* your 3 topics + fallback respond sensibly, and you've seen at least one answer's source.

### Step 7 — Improve your agent

Make three small upgrades (5–8 minutes):

1. Add a clarifying question where a question could mean two things — e.g. "Do you mean food donations or clothing donations?"
2. Refine the tone — read one answer aloud; warm it up or trim it to 2–3 sentences.
3. Add one safety boundary to your Instructions: "Do not ask for or store any personal information. If asked, politely decline and explain why."

> \\\*\\\*Quick check — done when:\\\*\\\* one topic asks a clarifying question, the tone feels friendly, and the agent refuses personal-data requests.

### Step 8 — Prepare for your demo

1. Pick your 3 best questions (test they all work).
2. Fill in the 1-slide template below.
3. Decide who talks and who types.
4. Have a backup screenshot of a good answer in case the live demo is slow.

> \\\*\\\*Tip:\\\*\\\* If your tenant allows it, you can Publish/share your agent so others can try it. If not, demoing in the Test panel is perfectly fine.

> \\\*\\\*Quick check — done when:\\\*\\\* you can run your 3 questions in under 2 minutes and your slide is filled in.

### Step 9 — Publish to Teams and test in the browser

**What you're doing:** publishing your agent to the Microsoft Teams channel and testing it in Teams on the web. **Why it matters:** this is how people often use agents in real life, and these laptops do not require the Teams desktop app.

1. In Copilot Studio, open Publish (or Publish/Channels) and click Publish latest content.
2. Wait for the publish to complete.
3. Click on +4 (to the right of Topics), Open Channels and select Microsoft 365 and Microsoft Teams.
4. Press Add channel.
5. select See agent in Teams.
6. Sign in to Teams in your browser and open your agent chat.
7. Press add. 
8. Press Open. 
7. Run the same 3 demo questions and verify answers still look right.

> \\\*\\\*Browser-only rule for this workshop:\\\*\\\* Use Teams on the web at https://teams.microsoft.com. Do not use the desktop app.

> \\\*\\\*If Teams opens the desktop app automatically:\\\*\\\* cancel it and return to the browser tab; choose "Use the web app instead".

> \\\*\\\*Quick check — done when:\\\*\\\* your agent is published, opens in Teams web, and answers your 3 test questions correctly.

\---

## Advanced (optional) — give your agent a Tool

For confident builders who finish early. A Tool lets your agent DO something or fetch live, up-to-date information — not just chat from fixed knowledge. Examples: look up data in another system, run an automated flow, or call a service.

> \\\*\\\*Heads-up:\\\*\\\* Some connectors are "Premium" and need a paid licence or admin approval. If you don't have those, use a Standard connector, build a simple Power Automate flow, or simulate the idea with a topic.

### How it works

1. Turn on generative orchestration in Settings — this lets the agent choose tools by itself.
2. Open the Tools (or Actions) area and choose Add a tool.
3. Pick a Standard connector action, create a new Power Automate flow (avoid Premium-marked ones) or add a REST API call.
4. Give the tool a clear name and a one-sentence description of exactly when to use it.
5. Map the inputs and outputs in plain language.
6. Save, then ask a question that needs the tool and watch the agent call it.

> \\\*\\\*Tip:\\\*\\\* The agent decides when to use a tool by reading its description. A clear "Use this when…" description is the most important part.

> \\\*\\\*Stay safe:\\\*\\\* Tools can send data out (e.g. a flow that emails someone). No real personal data, and only connect to things safe for a public/education setting.

\---

## Responsible \& safe use

* No personal data — don't ask for or store names, numbers, emails, or sensitive details.
* Be transparent — make it clear people are talking to an AI helper.
* Admit uncertainty — include an "I might be wrong" line.
* Stay in scope — point medical, legal, emergency or crisis questions to a real human.
* Escalate when it matters — always give a route to a person or official service.

> \\\*\\\*Copy this into your agent (Safety \\\& Scope):\\\*\\\* "Hi! I'm an AI helper here to answer general questions about \\\[your topic]. I'm not a person, and I might sometimes be wrong — please double-check anything important. I won't ask for or store any personal information. For urgent matters, or anything I can't help with, please contact \\\[the charity support team / a member of staff]. How can I help today?"

\---

## Your 2–3 minute demo

Structure: who \& what (20s) → why it matters (20s) → live demo of 3 best questions (60–90s) → one safety choice (15s) → one next step (15s).

### 1-slide template (fill this in)

> AGENT NAME: \\\_\\\_\\\_\\\_ | PROBLEM (one sentence): \\\_\\\_\\\_\\\_ | WHO IT'S FOR: \\\_\\\_\\\_\\\_ | WHAT IT DOES (2–3 bullets): \\\_\\\_\\\_\\\_ | DEMO QUESTIONS (3): \\\_\\\_\\\_\\\_ | SAFE-USE CHOICE: \\\_\\\_\\\_\\\_ | NEXT STEP: \\\_\\\_\\\_\\\_

\---

## If something goes wrong

|Problem|Quick fix|
|-|-|
|Can't sign in|Use a work/school/Microsoft account, not personal Gmail. Try a private window.|
|No "create agent" option|Accept the free trial, or ask a helper for a shared account.|
|Knowledge ignored|Save first; keep it short; check generative answers is on; re-ask using FAQ words.|
|Topic won't trigger|Add more trigger phrases (3–5); avoid single common words; Save and retest.|
|Answers too long|Add "Keep answers to 2–4 sentences" to Instructions.|
|Agent makes things up|Strengthen the fallback: "If unsure, say so and point to a human. Never guess."|
|Tool/connector blocked|It's probably Premium — use a Standard connector, a flow, or simulate with a topic.|
|Running out of time|Ship what you have. One great topic + a good fallback is a win.|

\---

## Useful links

* **Copilot Studio (web app):** https://copilotstudio.microsoft.com
* **Documentation home:** https://learn.microsoft.com/en-us/microsoft-copilot-studio/
* **Get started / create your first agent:** https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-get-started
* **Create \& edit topics:** https://learn.microsoft.com/en-us/microsoft-copilot-studio/authoring-create-edit-topics
* **Add knowledge sources:** https://learn.microsoft.com/en-us/microsoft-copilot-studio/knowledge-copilot-studio
* **Generative answers:** https://learn.microsoft.com/en-us/microsoft-copilot-studio/nlu-boost-conversations
* **Add tools / actions:** https://learn.microsoft.com/en-us/microsoft-copilot-studio/advanced-plugin-actions
* **Publish \& share:** https://learn.microsoft.com/en-us/microsoft-copilot-studio/publication-fundamentals-publish-channels
* **Teams on the web:** https://teams.microsoft.com

> \\\*\\\*You did it!\\\*\\\* If your agent answers a couple of real questions and handles "I don't know" gracefully, that's a genuine win. Celebrate it and keep the idea — you can grow it after today.

