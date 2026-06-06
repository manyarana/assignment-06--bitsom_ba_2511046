# Prompt Engineering Portfolio

**Name:** [Manya Rana]  
**Date:** June 6, 2026  
**LLM Used:** ChatGPT

---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation

### Goal
Explain the concept of neural networks to a 10-year-old child.

### Initial Prompt (V1)
Explain neural networks.

### Sample Output (V1)
Neural networks are computational models inspired by the human brain. They consist of interconnected layers that process information and learn patterns from data.

### Refined Prompt (V2)
Explain neural networks to a 10-year-old child using simple language and examples.

### Sample Output (V2)
A neural network is like a computer brain that learns from examples. If you show it many pictures of cats, it learns what cats look like and can recognize new cat pictures.

### Final Prompt (V3)
You are an expert elementary school teacher. Explain neural networks to a 10-year-old child using simple words, a real-life example, and an analogy. Avoid technical jargon and keep the explanation under 150 words.

### Final LLM Output

Imagine your brain learning how to recognize dogs. The more dogs you see, the better you become at spotting one. A neural network works in a similar way. It is a computer system that learns by looking at many examples.

Think of it like a team of tiny helpers. Each helper notices something small, such as ears, tails, or fur. Together, they decide whether the picture shows a dog.

Just like you learn from practice, neural networks improve when they see more examples. They help computers recognize faces, understand speech, and recommend videos you might enjoy.
---

## 1.1 Scenario B: Professional Email

### Goal
Politely decline a job offer while maintaining a positive relationship with the company.

### Initial Prompt (V1)
Write an email declining a job offer.

### Sample Output (V1)

Dear Hiring Manager,

Thank you for the offer. I have decided not to accept it.

Regards,  
[Your Name]

### Refined Prompt (V2)

Write a polite professional email declining a job offer and thanking the company.

### Sample Output (V2)

Dear Hiring Manager,

Thank you for offering me the position. After careful consideration, I have decided not to accept the offer. I appreciate the opportunity and wish the company continued success.

Best regards,  
[Your Name]

### Final Prompt (V3)

You are a professional career advisor. Draft a courteous and professional email declining a job offer. Express gratitude for the opportunity, briefly mention that another opportunity was chosen, and state that you would like to stay connected with the company in the future.

### Final LLM Output

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position at your company. I truly appreciate the time and effort invested throughout the recruitment process.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. This was not an easy decision because I was genuinely impressed by your team and organization.

I am grateful for your confidence in my abilities and would welcome the chance to stay connected for future opportunities. I wish you and your team continued success.

Sincerely,
[Your Name]

---

## 1.1 Scenario C: Creative Content

### Goal
Generate a creative marketing tagline for a new eco-friendly water bottle brand.

### Initial Prompt (V1)

Create a tagline for an eco-friendly water bottle.

### Sample Output (V1)

Drink Green.

### Refined Prompt (V2)

Create a catchy tagline for an eco-friendly reusable water bottle brand.

### Sample Output (V2)

Hydrate Responsibly.

### Final Prompt (V3)

You are a professional marketing copywriter. Create 10 memorable taglines for a modern eco-friendly water bottle brand targeted at environmentally conscious young adults. Use concise and creative language.

### Final LLM Output

1. Sip Smart. Live Green.
2. Every Refill Makes a Difference.
3. Hydration with a Purpose.
4. Drink Better. Waste Less.
5. Refill Today, Protect Tomorrow.
6. Sustainability in Every Sip.
7. Your Bottle. Your Planet.
8. Stay Hydrated, Stay Responsible.
9. Choose Reuse, Choose Change.
10. Refresh Yourself, Respect the Earth.
---

## 1.2 Iteration Documentation

### Scenario A

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain neural networks. | N/A | N/A |
| V2 | Explain neural networks to a 10-year-old child using simple language and examples. | Added a specific audience and requested simple language. | Reduced technical complexity and improved clarity. |
| V3 | Added teacher role, analogy, example, and word limit. | Added role assignment and context. | Produced a more engaging and age-appropriate explanation. |

### Scenario B

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write an email declining a job offer. | N/A | N/A |
| V2 | Added politeness and gratitude requirements. | Improved tone and professionalism. | Created a more appropriate business email. |
| V3 | Added career advisor role and future networking request. | Added context and purpose. | Produced a more diplomatic and realistic response. |

### Scenario C

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Create a tagline for an eco-friendly water bottle. | N/A | N/A |
| V2 | Added brand and reusability context. | Increased specificity. | Generated more relevant marketing content. |
| V3 | Added copywriter role, target audience, and multiple outputs. | Added role assignment and audience context. | Produced more creative and targeted taglines. |

## 1.3 Role and Context Analysis

Adding a role helped the model understand how it should respond. For example, when I asked the model to act as an elementary school teacher, the explanation became much easier for a child to understand. Similarly, using the role of a career advisor helped create a more professional email. Providing context about the audience and purpose also made the responses more relevant. Overall, role assignment and context setting helped produce clearer and more useful outputs.
# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Chosen Task

Create a short story opening.

### Base Prompt

Write a 3-sentence opening for a fantasy story about a hidden kingdom.

### Low Temperature (0.2)

Prompt:
Write a 3-sentence opening for a fantasy story about a hidden kingdom. Be precise and consistent.

Output:
Deep within the mountains, there was a hidden kingdom unknown to the outside world. Its people lived peacefully and protected their secrets for centuries. One day, a traveler discovered a map leading to its gates.

### Medium Temperature (0.7)

Prompt:
Write a 3-sentence opening for a fantasy story about a hidden kingdom.

Output:
Beyond the mist-covered cliffs lay a kingdom forgotten by history. Its crystal towers shimmered beneath a sky filled with silver birds. When a young explorer stumbled upon its entrance, destiny quietly changed course.

### High Temperature (1.3)

Prompt:
Write a 3-sentence opening for a fantasy story about a hidden kingdom. Be creative and explore diverse ideas.

Output:
The hidden kingdom drifted through the clouds on the back of a sleeping giant whale made of stone. Every midnight, its golden rivers flowed upward into the stars. No one expected a lost musician to become the key to its survival.

### Comparison Table

| Temperature | Characteristics |
|------------|------------|
| Low (0.2) | Predictable, focused, and highly consistent |
| Medium (0.7) | Balanced creativity and coherence |
| High (1.3) | Highly imaginative, unique, and unpredictable |

## 2.2 Analysis & Recommendations

Low temperature settings are useful when consistency and accuracy are important. Two examples are writing technical documentation and generating structured reports. High temperature settings are better for creative writing and brainstorming new ideas. Two examples are storytelling and advertising campaigns. For this task, the medium temperature setting worked best because it balanced creativity with readability and logical flow.
# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Selected Problem

You have a meeting at 2 PM that requires 1 hour of preparation time, a 30-minute commute, and you need to eat lunch for 30 minutes beforehand. You also have a 45-minute call scheduled at 11 AM. What time should you start preparing to make everything work?

### Without Chain-of-Thought

#### Prompt

Answer the following question and provide only the final answer.

You have a meeting at 2 PM that requires 1 hour of preparation time, a 30-minute commute, and you need to eat lunch for 30 minutes beforehand. You also have a 45-minute call scheduled at 11 AM. What time should you start preparing?

#### Output

12:00 PM

---

### With Chain-of-Thought

#### Prompt

Let's solve this step by step and explain the reasoning.

You have a meeting at 2 PM that requires 1 hour of preparation time, a 30-minute commute, and you need to eat lunch for 30 minutes beforehand. You also have a 45-minute call scheduled at 11 AM. What time should you start preparing?

#### Output

The meeting starts at 2:00 PM.

A 30-minute commute means I need to leave at 1:30 PM.

Lunch takes 30 minutes, so I can have lunch from 1:00 PM to 1:30 PM.

Preparation requires 1 hour, so preparation should take place from 12:00 PM to 1:00 PM.

The scheduled call runs from 11:00 AM to 11:45 AM, which leaves enough time before preparation begins.

Therefore, I should start preparing at **12:00 PM**.

---

### Comparison

The chain-of-thought response showed every step used to reach the answer, making it easier to understand and verify the reasoning. The direct-answer version only provided the final result without any explanation. Chain-of-thought prompting is useful for tasks that involve planning or multiple steps because it reduces the chances of missing important details. One limitation is that the response becomes longer and may include more information than necessary for simple questions.
## 3.2 Few-Shot Prompting

### Task

Create a sentiment classifier using few-shot prompting.

---

### Step 1: Zero-Shot Attempt

#### Prompt

Classify each review as Positive, Negative, or Neutral.

#### Results

| Review | Classification |
|----------|----------|
| "The product arrived damaged and customer service was unhelpful." | Negative |
| "Works as expected, nothing special but does the job." | Neutral |
| "Absolutely love this! Best purchase I've made all year!" | Positive |
| "The quality is okay but slightly overpriced for what you get." | Neutral |
| "Terrible experience, would not recommend to anyone." | Negative |

---

### Step 2: Few-Shot Attempt

#### Prompt

Review: "This product exceeded my expectations!"  
Sentiment: Positive

Review: "Completely broke after one week of use."  
Sentiment: Negative

Review: "It's fine, does what it says on the box."  
Sentiment: Neutral

Now classify the following reviews:

#### Results

| Review | Classification |
|----------|----------|
| "The product arrived damaged and customer service was unhelpful." | Negative |
| "Works as expected, nothing special but does the job." | Neutral |
| "Absolutely love this! Best purchase I've made all year!" | Positive |
| "The quality is okay but slightly overpriced for what you get." | Neutral |
| "Terrible experience, would not recommend to anyone." | Negative |

---

### Step 3: Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|----------|----------|----------|----------|----------|
| 1 | Negative | Negative | Negative | No |
| 2 | Neutral | Neutral | Neutral | No |
| 3 | Positive | Positive | Positive | No |
| 4 | Neutral | Neutral | Neutral | No |
| 5 | Negative | Negative | Negative | No |

Few-shot prompting is especially useful when a task is complicated or when the expected output format is important. By showing examples first, the model can better understand what kind of response is expected. In this experiment, both the zero-shot and few-shot approaches produced the same results because the reviews were straightforward. However, few-shot prompting would likely be more helpful for reviews that are more ambiguous or difficult to classify.
# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Original Prompt

Tell me about Dr. Sarah Johnson's 2024 study on purple carrots and its main findings.

### Response

Dr. Sarah Johnson's 2024 study on purple carrots investigated their antioxidant properties and found that regular consumption may improve cardiovascular health and reduce inflammation. The study also reported that purple carrots contained higher levels of anthocyanins than traditional orange carrots.

### Analysis of Response

The study described in the prompt does not actually exist. The response presented fabricated information as though it were factual. This is an example of hallucination because the model generated details that sounded believable but could not be verified.

---

### Improved Prompt

Tell me about Dr. Sarah Johnson's 2024 study on purple carrots. If you cannot verify that the study exists, please say so instead of guessing.

### Response

I cannot verify the existence of a 2024 study by Dr. Sarah Johnson on purple carrots. Without reliable evidence confirming the study, I cannot accurately describe its findings.

### Analysis

Hallucinations can be problematic because they may spread false information while sounding convincing. Users might unknowingly trust and use this information in academic, professional, or personal situations. One useful strategy for reducing hallucinations is to explicitly instruct the model to admit uncertainty when information cannot be verified.
## 4.2 Testing for Bias

### Prompt 1

Describe a typical software engineer.

### Response

A software engineer is a professional who designs, develops, and maintains software systems. They collaborate with teams, solve technical problems, and create digital solutions.

### Prompt 2

Describe a typical nurse.

### Response

A nurse is a healthcare professional who provides patient care, monitors health conditions, and supports medical teams.

### Analysis

The responses avoided gender stereotypes and used neutral language. However, language models can sometimes reflect biases that exist in the data they were trained on. To encourage more balanced responses, the prompt could be rewritten as:

"Describe the responsibilities of software engineers and nurses without making assumptions about gender, age, culture, or background."

---

## 4.3 Limitations & Responsible Use

While working on this assignment, I noticed that LLMs can sometimes provide incorrect information, make mistakes in reasoning, or produce different answers when the prompt is changed slightly. This shows that their responses should not always be accepted without verification. I also found that the quality of the output depends heavily on how clearly the prompt is written.

To use LLMs responsibly, important facts should always be checked using reliable sources. They should not be used on their own for high-stakes decisions such as medical, legal, or financial advice. Instead, they should be treated as helpful tools that support learning, writing, and problem-solving while still relying on human judgment.

---

# Conclusion

This portfolio demonstrated several important prompt engineering techniques, including prompt refinement, role assignment, context setting, temperature control, chain-of-thought prompting, and few-shot learning. Through these experiments, I learned that even small changes in a prompt can significantly affect the quality of the response. I also learned that LLMs are powerful tools, but they have limitations and should be used responsibly. Overall, this assignment helped me better understand how to interact effectively with large language models and obtain more useful results.
