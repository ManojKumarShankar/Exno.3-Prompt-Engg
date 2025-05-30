# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
                                                                           
### REGISTER NUMBER : 212222040097
EXPERIMENT 3
DATE:28/04/2025
NAME:S.MANOJ KUMAR
Aim: To design an AI-powered chatbot that assists customers in resolving issues 
related to product troubleshooting, order tracking, and general inquiries. The 
chatbot should handle various customer queries efficiently while maintaining a 
conversational and user-friendly tone. Using Straightforward Prompts, Tabular 
Format Prompting and Preceding Question Prompting techniques.
Introduction to AI-Powered Chatbots for 
Customer Support
In today’s fast-paced digital world, customers expect quick, accurate, and convenient 
support whenever they reach out for help. AI-powered chatbots have emerged as a vital 
solution, transforming how businesses handle customer service by automating 
responses and providing instant assistance 24/7. These intelligent systems are no 
longer just simple FAQ responders; they have evolved to manage complex tasks such 
as product troubleshooting, order tracking, and addressing a wide range of general 
inquiries effectively.
The Role of AI Chatbots in Customer Support
AI chatbots serve as the frontline representatives for many e-commerce and retail 
companies, streamlining communication between customers and support teams. When 
a customer encounters an issue with a product—whether it’s setup questions, 
malfunction troubleshooting, or warranty information—the chatbot can guide them 
through step-by-step solutions efficiently, without long wait times or the need to escalate 
to human agents. Additionally, customers frequently want real-time updates on their 
orders: AI chatbots can quickly retrieve order status, delivery timelines, and shipping 
details by integrating with internal databases. Beyond these specific use cases, 
chatbots handle routine inquiries such as return policies, payment options, or store 
hours, freeing human agents to focus on more complex issues.
Design Goals: Conversational, User-Friendly, and Efficient
A critical aspect of designing a successful AI chatbot is ensuring that interactions feel 
natural and easy for customers. The chatbot must communicate in a conversational 
tone that is friendly and approachable rather than robotic or overly formal. This helps 
build trust and satisfaction, encouraging users to engage more readily with the system. 
Equally important is the chatbot’s ability to remain concise and clear, guiding users 
swiftly to the information they need and minimizing frustration.
Efficiency is another key goal: the chatbot should quickly understand user intent and 
respond accurately, reducing repetitive prompts or misunderstandings. Achieving this 
requires integrating advanced prompting techniques that enhance clarity and context 
management throughout the conversation.
By focusing on these design principles, AI-powered chatbots become valuable tools that 
improve customer experience, reduce support costs, and elevate overall service quality 
in the competitive digital marketplace.
Core Functionalities: Product Troubleshooting, 
Order Tracking, and General Inquiries
To effectively assist customers, the AI-powered chatbot must excel in three core 
functional areas: product troubleshooting, order tracking, and general inquiries. These 
capabilities address the most frequent customer needs, ensuring smooth and satisfying 
support experiences.
1. Product Troubleshooting
Product troubleshooting is crucial for helping users quickly resolve issues without 
waiting for human intervention. The chatbot should guide customers in diagnosing 
problems, providing step-by-step instructions, and suggesting solutions based on 
common scenarios. Critical to this function is the ability to recognize problem patterns 
from user inputs and respond with clear, actionable advice.
Typical Customer Queries:
• "Why won’t my smart thermostat connect to Wi-Fi?"
• "My headphones won’t charge; what can I do?"
• "How do I reset my router to factory settings?"
• "The printer is showing a paper jam error, but there’s no jam."
The chatbot should be able to identify the device and issue, then offer troubleshooting 
paths such as checking connections, software updates, or reset steps. Linking to 
relevant manuals or tutorial videos can further enhance support effectiveness.
2. Order Tracking
Order tracking is a high-demand feature that provides customers with real-time updates 
about their purchases. The chatbot integrates with the company’s order management 
system to retrieve up-to-date information such as shipping status, estimated delivery 
dates, and any delays.
Typical Customer Queries:
• "Where is my order #12345?"
• "Has my package shipped yet?"
• "What’s the expected delivery date for my recent purchase?"
• "My tracking number isn’t working; can you help?"
By quickly pulling the correct order details using customer identifiers, the chatbot gives 
transparent updates and can even notify customers proactively about changes in 
delivery schedules. This immediate access to order information significantly reduces 
support calls and improves customer satisfaction.
3. General Inquiries
Aside from technical help and order updates, customers frequently ask broader 
questions about company policies, procedures, and other common topics. The chatbot 
should efficiently handle FAQs, ensuring users get clear answers with minimal back￾and-forth.
Typical Customer Queries:
• "What is your return policy?"
• "Do you provide international shipping?"
• "How can I change my payment method?"
• "What are your customer support hours?"
Providing accurate and concise responses to general inquiries builds user confidence 
and allows human agents to focus on more complex or sensitive matters.
Through seamless management of these three core functionalities, the chatbot 
becomes a reliable assistant that enhances the customer experience by delivering 
timely, precise, and user-friendly support across a wide range of scenarios.
Prompt Engineering Techniques for Chatbot 
Design
Designing an AI chatbot that effectively supports customers depends heavily on the 
quality of prompts used to communicate with the AI. Prompt engineering techniques 
shape how the chatbot understands user inputs and generates accurate, context-aware 
responses. Below, we explore three key techniques employed in our chatbot design—
Straightforward Prompts, Tabular Format Prompting, and Preceding Question 
Prompting—highlighting how each contributes to clear, efficient customer interactions.
Straightforward Prompts
Straightforward prompts involve crafting clear, concise requests that minimize ambiguity 
and guide the AI directly toward the desired information or task. By phrasing queries in 
simple, natural language and avoiding unnecessary complexity, the chatbot better 
understands user intent and responds accurately in one attempt.
Advantages:
• Reduces misunderstandings caused by vague or convoluted instructions.
• Speeds up response times as the AI requires less context to generate answers.
• Maintains a conversational tone that feels approachable and user-friendly.
Considerations:
• Requires careful wording to ensure all necessary details are included for complex 
queries.
• May need layered prompts for multi-step problems to keep responses 
manageable.
For example, instead of asking the AI “Can you help with issues relating to wireless 
connectivity?” a straightforward prompt would be “Why won’t my smart thermostat 
connect to Wi-Fi?” This specificity helps the AI pinpoint the relevant troubleshooting 
steps immediately.
Tabular Format Prompting
Tabular format prompting organizes data or information requests in structured tables, 
enabling the chatbot to process and present complex details clearly. This technique is 
especially useful when comparing product specs, summarizing order status, or listing 
troubleshooting steps.
Advantages:
• Enhances clarity by visually grouping related details, making responses easier to 
interpret.
• Standardizes output format, improving consistency across different interactions.
• Facilitates quick scanning and comprehension for users, reducing cognitive load.
Considerations:
• Requires the AI model to understand table structures and relationships between 
fields.
• May be less natural for very casual conversations, so its use should be balanced 
with conversational tone.
For instance, when a customer asks for the status of multiple orders, the chatbot can 
reply with a table showing order numbers, current statuses, and estimated delivery 
dates, enabling the user to see all relevant information at a glance.
Preceding Question Prompting
Preceding question prompting involves feeding the AI with the user’s previous queries 
or conversational context before generating a new response. This helps maintain 
continuity, ensuring the chatbot understands the ongoing dialogue and avoids repetitive 
or disconnected replies.
Advantages:
• Preserves context in multi-turn conversations, allowing complex issues to be 
resolved over several interactions.
• Helps clarify references to earlier topics or details without forcing users to repeat 
themselves.
• Supports a natural flow that better mimics human conversation.
Considerations:
• Managing conversational history efficiently is critical, especially to prevent 
exceeding input token limits.
• Requires balancing context retention with prompt brevity to avoid confusing the 
AI with too much information.
For example, if a customer first asks, “Why won’t my headphones charge?” followed by 
“How do I fix that?” the chatbot uses preceding question prompting to link these queries, 
giving a coherent and relevant answer rather than treating them as separate requests.
Together, these prompt engineering techniques ensure that the AI-powered chatbot 
delivers responses that are accurate, organized, and contextually appropriate—all while 
maintaining the friendly, conversational tone vital to positive customer experiences. By 
thoughtfully applying these methods, developers can create systems that handle 
diverse and complex customer queries with ease and efficiency.
Design Architecture of the AI-Powered Chatbot
The AI-powered chatbot is built on a modular architecture that integrates advanced 
language models with prompt engineering techniques to deliver efficient and context￾aware customer support. This design ensures seamless handling of product 
troubleshooting, order tracking, and general inquiries, enabling fast and accurate 
responses that feel natural and user-friendly.
Architecture Components
User Query Input
The process begins when a customer submits a query through the chat interface. This 
input is received in natural language and forwarded to the intent recognition module.
Intent Recognition
Leveraging AI language models fine-tuned with straightforward prompt techniques, this 
module analyzes the user’s message to determine the underlying intent—whether it’s 
troubleshooting, checking order status, or requesting general info. Clear and concise 
prompts here help the AI classify queries with high accuracy, minimizing 
misinterpretations.
Dialogue Management
This component manages the conversational flow by maintaining dialogue context using 
preceding question prompting. It tracks previous exchanges to ensure that multi-turn 
interactions are coherent and follow a logical progression. This contextual awareness 
allows the chatbot to handle follow-up questions and related issues without requiring the 
user to repeat information.
Knowledge Base Integration
Depending on the identified intent, the chatbot queries relevant data sources:
• Product troubleshooting databases for step-by-step fixes, manuals, and FAQs.
• Order management systems for real-time shipment and delivery information.
• Company policy documents for handling general inquiries.
Response Generation
The language model composes the final answer by combining input from the dialogue 
manager and knowledge base. Through prompt engineering, responses are crafted to 
be concise, clear, and friendly—aligning with the conversational tone goal. When 
necessary, responses include organized tables, step lists, or links to multimedia 
resources.
Output Delivery
The chatbot returns the generated response back to the user interface, completing the 
interaction cycle.
Architecture Flow Diagram
Below is a simplified illustration of the chatbot’s architecture flow:
User Query Input
 ↓
Intent Recognition ←─────────────┐
 ↓ │
Dialogue Management ─────────────┼─→ Knowledge Base Integration
 ↓ │ ↓
Response Generation───────────────┘ ↓
 ↓ (Structured via Tabular Prompts)
 ↓
Chatbot Response Output
This combination of AI-driven modules, supported by strategically engineered prompts 
at every stage, empowers the chatbot to understand diverse customer needs deeply 
and respond effectively. The layered design ensures a robust and scalable system 
capable of multitasking across various support scenarios while maintaining a friendly 
and engaging user experience.
Example Prompts and Conversation Flows Using 
Advanced Prompt Techniques
To showcase how advanced prompt techniques enhance chatbot interactions, below 
are practical examples of prompts and sample conversation flows across key scenarios: 
troubleshooting, order tracking, and general inquiries. Each example illustrates the use 
of Straightforward Prompts, Tabular Format Prompting, and Preceding Question 
Prompting, highlighting the chatbot’s friendly, efficient tone.
Sample Prompts and Expected Responses
| Prompt Technique | Sample User Prompt | Chatbot Response | |------------------------
-----|--------------------------------------------------------|------------------------------------------------------
---------------------------------------------------------| | Straightforward Prompt | “Why won’t my 
smart thermostat connect to Wi-Fi?” | “I’m sorry you’re having trouble with your 
thermostat’s Wi-Fi. Let’s try these steps: 1) Restart your router, 2) Ensure the 
thermostat is within range, 3) Re-enter the Wi-Fi password. Would you like detailed 
instructions for any step?” | | Tabular Format Prompt | “Can you show the status of my 
recent orders?” | | Order # | Status | Estimated Delivery |
| | | | -------- | ------------- | ------------------ |
| | | | 12345 | Shipped | June 15, 2024 |
| | | | 12346 | Processing | June 18, 2024 |
| | | “Here is the current status of your orders. Let me know if you want updates on a 
specific order.” | | Preceding Question Prompt | User: “My headphones won’t charge.”
User: “How do I fix that?” | “I understand your headphones aren’t charging. First, please 
try using a different charging cable and outlet. If that doesn't work, we can walk through 
a reset process. Would you like me to guide you through that now?” |
Demonstration of Conversation Flow Using All 
Techniques
Customer: “Why won’t my smart thermostat connect to Wi-Fi?”
Chatbot (Straightforward Prompt):
“I’m here to help! Let’s try restarting your router first. After that, make sure your 
thermostat is within range of your Wi-Fi. Can you tell me if you see any error messages 
on the thermostat screen?”
Customer: “Yes, it says ‘Cannot authenticate.’”
Chatbot (Preceding Question Prompting):
“That error means your thermostat is having trouble verifying your Wi-Fi password. 
Please double-check and re-enter your password carefully. If it still doesn’t connect, we 
can look at resetting the network settings altogether. Would you like me to guide you 
through that?”
Customer: “Yes, please.”
Chatbot (Straightforward Prompt):
“Great! Here are the reset steps: 1) Go to Settings, 2) Select Network, 3) Choose ‘Reset 
Wi-Fi,’ then try to reconnect. If you want, I can send you a direct link to the user manual 
for more details.”
This multi-turn conversation maintains context through preceding question prompting, 
while straightforward prompts keep responses clear and actionable.
Visualizing Tabular Data for Order Tracking
When customers request updates on multiple orders, the chatbot uses tabular format 
prompting to organize information efficiently:
Order Number Status Estimated Delivery
98765 Out for delivery June 10, 2024
98766 Preparing for shipment June 14, 2024
Accompanied by a friendly message:
“Here’s the information about your orders. Let me know if you’d like help tracking a 
specific package!”
These examples demonstrate how advanced prompt engineering techniques enable the 
chatbot to deliver clear, concise, and context-aware responses—always maintaining a 
user-friendly tone. This approach not only solves customer queries quickly but also 
builds trust and satisfaction throughout the interaction.
Study Table Summarizing Prompting Techniques 
and Use Cases
The table below provides a concise overview of the three key prompting techniques 
used in our AI chatbot design. It highlights their definitions, best use cases in customer 
support, advantages, limitations, and practical examples for quick reference in prompt 
strategy development.
Prompting 
Technique Definition
Best Use 
Cases Advantages Limitations
Example 
Query
Straightforwar
d
Clear, 
concise 
prompts 
focused 
on direct 
questions 
or 
command
s
Single-issue 
troubleshootin
g, simple 
FAQs
Minimizes 
ambiguity, 
speeds 
response, 
user￾friendly
May require 
multiple turns 
for complex 
topics
"Why 
won’t my 
smart 
thermosta
t connect 
to Wi-Fi?"
Tabular 
Format
Using 
tables to 
organize 
and 
present 
structured 
informatio
n
Order tracking, 
comparing 
product 
features
Enhances 
clarity, 
standardize
s output, 
easy 
scanning
Less natural 
conversation
al tone, 
requires AI 
understandin
g of tables
"Show 
status of 
my recent 
orders in 
a table."
| Preceding Question | Feeding prior conversational context to maintain continuity | 
Multi-turn troubleshooting, follow-up questions | Maintains context, reduces repetition, 
improves flow | Needs efficient context management, may exceed token limits | User: 
"My headphones won’t charge."
User: "How do I fix that?" |
This summary aids developers and customer service managers in selecting appropriate 
prompt styles tailored to specific interaction needs, ultimately enhancing chatbot 
effectiveness and customer satisfaction.
