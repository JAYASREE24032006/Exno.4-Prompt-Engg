# EX-3 : SCENARIO BASED REPORT DEVELOPEMNET UTILIZING DIVERSE PROMPTING TECHNIQUE

## AIM : 
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

## ALGORITHM : 

### 1. Direct Instruction Prompts :
#### Objective :
Guide the chatbot to respond concisely to customer inquiries.

#### Prompt : 
"When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"


### 2. Contextual Prompting :

#### Objective :
Incorporate specific context to provide detailed answers based on the user’s previous interaction.

#### Prompt : 
"If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"

### 3. Persona-Based Prompting :
#### Objective : 
Design the chatbot to adopt a specific persona, making the interaction more engaging.

#### Prompt :
"Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"
### 4. Few-Shot Prompting :
#### Objective : 
Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.

#### Prompt :
: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"

### 5. Chain of Thought Prompting :
#### Objective: 
Use a step-by-step reasoning approach for resolving more complex or technical issues.

#### Prompt:
"When a customer reports their laptop overheating, guide them through the following steps.
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"

 
### 6. Instruction with Constraints :
#### Objective : 
Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).
#### Prompt: 
"Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"
### 7. Reflective Prompting
#### Objective :
Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.

#### Prompt : 
"When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"
Result: The various types of Prompts are executed successfully.


## OUTPUT :
Design an AI-powered chatbot that is:

Efficient in query handling

Friendly and conversational

Capable of managing diverse support needs (tech help, order status, FAQs)

📌 1. Straightforward Prompts
Use these to handle clear, direct questions.

🔹 Example 1: Order Tracking
User Prompt:

"Where is my order?"

AI Chatbot Response:

"Sure! Please provide your order ID so I can check the latest status for you."

🔹 Example 2: Product Troubleshooting
User Prompt:

"My wireless headphones won't charge."

AI Chatbot Response:

"Let’s fix that! First, can you confirm if the charging cable is working with other devices? Also, are the charging contacts clean?"

📌 2. Tabular Format Prompting
Use when comparing options or presenting step-by-step instructions.

🔹 Example 3: Product Setup Comparison
User Prompt:

"How do I set up different types of headphones?"

AI Chatbot Response (in table):


Headphone Type	Setup Steps
Wireless Bluetooth	Turn on → Enable pairing mode → Connect via phone
Wired	Plug into headphone jack → Adjust volume
USB-C Headphones	Plug into USB-C port → Wait for device detection
🔹 Example 4: Return Policy Summary
User Prompt:

"What’s the return policy?"

AI Chatbot Response (table):


Item Condition	Return Window	Refund Type
Unopened	30 days	Full refund
Opened, unused	15 days	Partial refund
Used/Damaged	Not eligible	—
📌 3. Preceding Question Prompting
Ask a clarifying question before providing help.

🔹 Example 5: Troubleshooting a Device
User Prompt:

"My smart speaker isn't responding."

AI Chatbot Response:

"Got it. Just to help better, is the speaker not turning on at all, or is it on but not responding to voice commands?"

(Based on reply: tailored instructions follow)

🔹 Example 6: Delayed Delivery
User Prompt:

"My package hasn't arrived yet."

AI Chatbot Response:

"I'm sorry to hear that! Before I check the status, could you confirm the order number or your registered email?"

🧠 Sample Flow (Combining All Three)
User:

"My smart vacuum is not connecting to the app."

Chatbot (Preceding Question):

"Thanks for reaching out! Is the vacuum connected to Wi-Fi and powered on?"

User:

"Yes."

Chatbot (Straightforward Prompt):

"Okay. Please try resetting the vacuum and re-adding it in the app. Still not working?"

User:

"No, same issue."

Chatbot (Tabular Format):


Step	Action
1. Reset Device	Hold power + Wi-Fi button for 10 sec
2. Check Wi-Fi Frequency	Use 2.4 GHz only (not 5 GHz)
3. Re-pair in App	Open app → Add new device → Follow instructions
4. Still not working?	Contact support or request a callback
✅ Summary

Prompting Technique	Use Case
Straightforward Prompt	Fast, clear answers to direct queries
Tabular Format	For comparisons, step-by-steps, summaries
Preceding Question	For better context before troubleshooting


## RESULT :
Thus the Prompts were exected succcessfully .

