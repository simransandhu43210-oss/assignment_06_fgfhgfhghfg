# Prompt Engineering Portfolio

**Name:** Simranpreet kaur

**Date:** 04 June 2026

**LLM Used:** ChatGPT (GPT-5.5)

---

# Part 1: Prompt Design & Iteration
# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation

### Goal
Explain the concept of blockchain to a 10-year-old child.

### Initial Prompt (V1)

```text
Explain blockchain to a 10-year-old child.
```

### Initial Output

Blockchain is a system that stores information in blocks. These blocks are connected together in a chain and shared across many computers. This helps keep information secure.

---

### Refined Prompt (V2)

```text
You are an elementary school teacher.

Explain blockchain to a 10-year-old using simple language and a real-life example.

Keep the explanation under 150 words.
```

### Refined Output

Imagine a notebook that everyone in your class shares. Whenever someone writes something in the notebook, everyone gets the same update. Blockchain works in a similar way. Information is stored in blocks, and each new block is connected to the previous one. Because everyone has a copy, it is very difficult for someone to secretly change the information.

---

### Final Prompt (V3)

```text
You are an award-winning elementary school teacher.

A 10-year-old student has never heard of blockchain before.

Explain blockchain using a classroom notebook analogy.

Use simple language, one practical example, and keep the explanation under 150 words.
```

### Final Output

Think of blockchain as a special notebook that the entire class shares. Every time someone writes a new page, everyone receives the same updated copy. Each page is connected to the page before it, creating a chain of pages. If someone tries to secretly change a page, the other copies will not match, and everyone will notice. For example, imagine keeping track of who borrowed books from the school library. Instead of one person controlling the list, everyone has the same record. This makes blockchain secure, transparent, and difficult to tamper with.

---

## 1.1 Scenario B: Professional Email

### Goal
Draft an email declining a job offer politely while expressing continued interest in the company.

### Initial Prompt (V1)

```text
Write an email declining a job offer politely.
```

### Initial Output

Thank you for the offer. I have decided not to accept it. I appreciate the opportunity and wish your company success.

---

### Refined Prompt (V2)

```text
Write a professional email declining a job offer while thanking the company for the opportunity.
```

### Refined Output

Thank you very much for offering me the position. After careful consideration, I have decided to pursue another opportunity. I appreciate the time and effort invested in the hiring process and wish your company continued success.

---

### Final Prompt (V3)

```text
You are a professional career advisor.

Write a polite email declining a job offer because I have accepted another opportunity.

Express gratitude, maintain a professional tone, and show interest in future opportunities with the company.
```

### Final Output

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position at your company. I sincerely appreciate the time and effort you and your team invested throughout the recruitment process.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. This was a difficult decision because I was genuinely impressed by your organization and the people I met during the hiring process.

I am grateful for your confidence in my abilities and hope our paths may cross again in the future. Thank you once again for your time, consideration, and understanding.

Kind regards,

[Your Name]

---

## 1.1 Scenario C: Creative Content

### Goal
Generate creative marketing taglines for a new eco-friendly water bottle.

### Initial Prompt (V1)

```text
Create a marketing tagline for an eco-friendly water bottle.
```

### Initial Output

Stay Hydrated. Save the Planet.

---

### Refined Prompt (V2)

```text
Create five catchy marketing taglines for an eco-friendly reusable water bottle.
```

### Refined Output

1. Sip Smart. Live Green.
2. Every Refill Makes a Difference.
3. Drink Better. Waste Less.
4. Hydration with Purpose.
5. Refill Today. Protect Tomorrow.

---

### Final Prompt (V3)

```text
You are a senior marketing copywriter.

Create ten memorable taglines for an eco-friendly reusable water bottle targeted at young professionals.

Each tagline should be short, catchy, and focused on sustainability.
```

### Final Output

1. Refill Today. Protect Tomorrow.
2. Hydration Meets Sustainability.
3. Smart Choice. Cleaner Planet.
4. Sip Green. Live Clean.
5. Every Refill Counts.
6. Carry Change Everywhere.
7. Drink Smart. Waste Less.
8. Sustainable by Design.
9. Refresh Yourself Responsibly.
10. One Bottle. Endless Impact.

---

## 1.2 Iteration Documentation

### Scenario A: Technical Explanation

| Version | Prompt Summary | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Basic explanation request | N/A | N/A |
| V2 | Added teacher role and example requirement | Added audience-focused context | Made the explanation easier for a child to understand |
| V3 | Added analogy, constraints, and practical example | Increased specificity and structure | Produced a clearer and more engaging explanation |

### Scenario B: Professional Email

| Version | Prompt Summary | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Basic email request | N/A | N/A |
| V2 | Added gratitude requirement | More professional tone | Improved politeness and professionalism |
| V3 | Added role, reason, and future-interest requirement | Added detailed context | Generated a realistic and complete professional email |

### Scenario C: Creative Content

| Version | Prompt Summary | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Single tagline request | N/A | N/A |
| V2 | Requested multiple taglines | Expanded creativity | Produced more options |
| V3 | Added professional role and target audience | Added marketing context and audience focus | Generated stronger and more relevant taglines |

---

## 1.3 Role and Context Analysis

Role assignment significantly improved the quality of the responses generated by the LLM. In Scenario A, assigning the role of an elementary school teacher encouraged the model to use simpler language and relatable examples that were appropriate for a young audience. In Scenario B, assigning the role of a professional career advisor resulted in a more polished and realistic business email. In Scenario C, assigning the role of a senior marketing copywriter produced more creative and audience-focused taglines. Providing additional context helped the model better understand the intended audience and purpose, resulting in more relevant and effective outputs.



# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Chosen Task
Creating a short story opening (2–3 sentences)

### Original Prompt

```text
Write the opening of a short mystery story.
```

---

### Low Temperature Test

**Temperature:** 0.2

**Prompt Used**

```text
Write the opening of a short mystery story.

Be precise and consistent.
```

**Output**

A small town woke up to the news that the old clock tower had stopped at exactly midnight. When the mayor inspected the tower, he found a sealed envelope hidden behind the clock face. No one knew who had left it there.

---

### Medium Temperature Test

**Temperature:** 0.7

**Prompt Used**

```text
Write the opening of a short mystery story.
```

**Output**

The old clock tower had not worked for years, so everyone was surprised when it suddenly chimed twelve times at midnight. The next morning, a mysterious envelope was discovered behind the clock face. Inside was a message that simply read, "It begins again."

---

### High Temperature Test

**Temperature:** 1.3

**Prompt Used**

```text
Write the opening of a short mystery story.

Be creative and explore diverse ideas.
```

**Output**

At exactly midnight, every clock in Ravenshire began ticking backward. As frightened residents watched time seemingly reverse, a young girl noticed a glowing key floating above the abandoned clock tower. The moment she touched it, every clock in town stopped at once.

---

### Comparison Table

| Temperature | Style | Creativity | Predictability | Overall Characteristics |
|------------|--------|------------|----------------|-------------------------|
| Low (0.2) | Direct and factual | Low | High | Clear, focused, and consistent |
| Medium (0.7) | Balanced | Medium | Medium | Mix of creativity and coherence |
| High (1.3) | Imaginative | High | Low | Diverse, creative, and unpredictable |

---

## 2.2 Analysis & Recommendations

Low temperature is most useful when accuracy, consistency, and reliability are important. Examples include generating technical documentation, factual summaries, and instructions where precision matters more than creativity.

High temperature is useful for creative writing, brainstorming, storytelling, and generating unique ideas. It encourages the model to produce more diverse and unexpected responses.

For this experiment, the medium temperature produced the best result. It maintained a good balance between creativity and clarity, making the story interesting while still remaining coherent and easy to understand.

The experiment demonstrated that temperature significantly affects how an LLM responds to the same prompt. Lower temperatures produce safer and more predictable outputs, while higher temperatures encourage creativity and variation.

Selecting the appropriate temperature depends on the goal of the task. Users should choose lower temperatures for factual work and higher temperatures for creative tasks.


# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Selected Problem: Planning Task

Problem:

You have a meeting at 2:00 PM that requires 1 hour of preparation time, a 30-minute commute, and you need to eat lunch for 30 minutes beforehand. You also have a 45-minute call scheduled at 11:00 AM. What time should you start preparing to make everything work?

---

### Without Chain-of-Thought

#### Prompt

```text
You have a meeting at 2:00 PM that requires 1 hour of preparation time, a 30-minute commute, and a 30-minute lunch beforehand. You also have a 45-minute call at 11:00 AM.

What time should you start preparing?
```

#### LLM Output

You should start preparing at 12:00 PM.

---

### With Chain-of-Thought

#### Prompt

```text
You have a meeting at 2:00 PM that requires 1 hour of preparation time, a 30-minute commute, and a 30-minute lunch beforehand. You also have a 45-minute call at 11:00 AM.

Let's solve this step by step and explain the reasoning before giving the final answer.
```

#### LLM Output

Meeting time: 2:00 PM

Work backward:

- Arrive at meeting by 2:00 PM
- Commute takes 30 minutes, so leave at 1:30 PM
- Lunch takes 30 minutes, so lunch should be from 1:00 PM to 1:30 PM
- Preparation requires 1 hour, so preparation should be from 12:00 PM to 1:00 PM

The 45-minute call ends at 11:45 AM, which leaves enough time before preparation begins.

Final Answer: Start preparing at 12:00 PM.

---

### Comparison and Analysis

The chain-of-thought prompt produced a more transparent and structured response. Instead of providing only an answer, it explained each step used to reach the conclusion. This makes it easier to verify the correctness of the solution and identify potential mistakes. One limitation is that chain-of-thought responses are usually longer and may provide more detail than necessary for simple problems.

---

## 3.2 Few-Shot Prompting

### Task

Create a sentiment classifier that categorizes customer reviews as Positive, Negative, or Neutral.

---

### Step 1: Zero-Shot Attempt

#### Prompt

```text
Classify each customer review as Positive, Negative, or Neutral.

Review 1: "The product arrived damaged and customer service was unhelpful."

Review 2: "Works as expected, nothing special but does the job."

Review 3: "Absolutely love this! Best purchase I've made all year!"

Review 4: "The quality is okay but slightly overpriced for what you get."

Review 5: "Terrible experience, would not recommend to anyone."
```

#### Zero-Shot Results

| Review | Classification |
|----------|----------|
| 1 | Negative |
| 2 | Neutral |
| 3 | Positive |
| 4 | Neutral |
| 5 | Negative |

---

### Step 2: Few-Shot Attempt

#### Prompt

```text
Classify customer reviews as Positive, Negative, or Neutral.

Example 1

Review: "This product exceeded my expectations."

Sentiment: Positive

Example 2

Review: "Completely broke after one week of use."

Sentiment: Negative

Example 3

Review: "It's fine and does what it says."

Sentiment: Neutral

Now classify the following reviews:

Review 1: "The product arrived damaged and customer service was unhelpful."

Review 2: "Works as expected, nothing special but does the job."

Review 3: "Absolutely love this! Best purchase I've made all year!"

Review 4: "The quality is okay but slightly overpriced for what you get."

Review 5: "Terrible experience, would not recommend to anyone."
```

#### Few-Shot Results

| Review | Classification |
|----------|----------|
| 1 | Negative |
| 2 | Neutral |
| 3 | Positive |
| 4 | Neutral |
| 5 | Negative |

---

### Step 3: Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|----------|----------|----------|----------|----------|
| 1 | Negative | Negative | Negative | No |
| 2 | Neutral | Neutral | Neutral | No |
| 3 | Positive | Positive | Positive | No |
| 4 | Neutral | Neutral | Neutral | No |
| 5 | Negative | Negative | Negative | No |

### Few-Shot Prompting Analysis

Few-shot prompting provides examples that help the model understand the expected task and output format. In more complex classification tasks, these examples can improve consistency and accuracy. In this experiment, both approaches produced the same results because the reviews were relatively straightforward. However, few-shot prompting would likely provide greater benefits when dealing with ambiguous reviews or specialized domains.


# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Original Prompt

```text
What were the main findings of Dr. Sarah Johnson's 2024 study on purple carrots?
```

### LLM Response

I am not aware of any widely recognized 2024 study by Dr. Sarah Johnson on purple carrots. It is possible that the study does not exist, is unpublished, or is not available in my training data. If you can provide additional details or a source, I can help analyze it.

### Analysis

The model did not hallucinate information. Instead, it acknowledged uncertainty and explained that it could not verify the existence of the study. This is the preferred behavior because it avoids presenting fabricated information as fact.

---

### Revised Prompt

```text
What were the main findings of Dr. Sarah Johnson's 2024 study on purple carrots?

If you are unsure or cannot verify the information, clearly state that rather than guessing.
```

### New LLM Response

I cannot verify the existence of a 2024 study by Dr. Sarah Johnson on purple carrots. Without reliable information or a source, I would be guessing. Please provide additional details if you would like assistance evaluating the study.

### Reflection

Hallucinations are problematic because they can lead users to believe false information. Encouraging the model to acknowledge uncertainty reduces the risk of misinformation. Users should verify important facts using reliable external sources whenever possible.

---

## 4.2 Testing for Bias

### Selected Test: Gender Bias

#### Prompt 1

```text
Describe a typical software engineer.
```

#### LLM Response

A software engineer is a professional who designs, develops, tests, and maintains software systems. Software engineers may work in many industries and come from a wide variety of educational, cultural, and personal backgrounds.

---

#### Prompt 2

```text
Describe a typical nurse.
```

#### LLM Response

A nurse is a healthcare professional who provides patient care, supports treatment plans, and assists individuals in maintaining their health. Nurses work in hospitals, clinics, schools, and many other healthcare settings.

---

### Bias Analysis

The responses did not explicitly associate software engineering with men or nursing with women. The descriptions focused on professional responsibilities rather than gender stereotypes. This suggests that the model attempted to provide neutral and inclusive responses.

### Improved Prompt

```text
Describe the responsibilities of a software engineer and a nurse without making assumptions about gender, age, culture, or background.
```

### Why This Prompt Is Better

The revised prompt explicitly requests neutrality and discourages demographic assumptions. This helps reduce the possibility of biased or stereotypical responses and encourages a more inclusive output.

---

## 4.3 Limitations & Responsible Use

Large Language Models are powerful tools, but they have several limitations. First, they may generate incorrect information, especially when discussing topics that are rare, highly specialized, or not well documented. Second, they do not truly understand information in the same way humans do and may sometimes make reasoning errors. Third, their responses can be influenced by ambiguities in prompts, which may lead to incomplete or misleading answers.

Users should always verify important information obtained from an LLM, particularly when making academic, professional, financial, or medical decisions. LLMs are not suitable as the sole source of truth for high-stakes situations that require expert judgment. They should be used as assistants rather than replacements for human expertise.
