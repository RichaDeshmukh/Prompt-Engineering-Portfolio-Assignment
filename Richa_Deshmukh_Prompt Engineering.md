# Prompt Engineering Portfolio

**Name:** Richa Deshmukh
**Date:** 06 June 2026  
**LLM Used:** ChatGPT (GPT-5.5)

---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation

### Goal
Explain Neural Networks to a 10-year-old child.

### Initial Prompt (V1)
 Explain neural networks.
**Prompt:**
A neural network is a type of machine learning model inspired by the way biological neurons in the brain are connected. It learns patterns from data and can be used for tasks like image recognition, language translation, speech processing, and prediction.

Basic Structure

A neural network consists of layers of interconnected nodes (neurons):

Input Layer
Receives the raw data (e.g., pixels of an image, words in a sentence).
Hidden Layers
Process the information through mathematical operations.
Each neuron combines inputs, applies weights and biases, then passes the result through an activation function.
Output Layer
Produces the final prediction or decision.
Input → Hidden Layer(s) → Output
How a Neuron Works

A neuron computes:

z=w
1
	​

x
1
	​

+w
2
	​

x
2
	​

+⋯+w
n
	​

x
n
	​

+b

Then applies an activation function such as ReLU or sigmoid to produce the output.

Learning Process

Neural networks learn through a process called training:

Make a prediction.
Compare the prediction to the correct answer.
Calculate the error (loss).
Adjust the weights to reduce the error.
Repeat many times.

The adjustment step is typically done using:

Backpropagation (computes how much each weight contributed to the error)
Gradient Descent (updates weights to minimize error)
Example: Cat vs. Dog Classifier

Suppose you show a network thousands of labeled images of cats and dogs.

Input: Image pixels
Hidden layers: Learn features such as edges, ears, eyes, and fur patterns
Output: Probability that the image contains a cat or a dog

Over time, the network learns which visual patterns correspond to each animal.

Types of Neural Networks
Feedforward Neural Networks (FNNs): Basic architecture.
Convolutional Neural Networks (CNNs): Excellent for images and video.
Recurrent Neural Networks (RNNs): Designed for sequences and time-series data.
Transformers: Power modern AI systems and large language models like ChatGPT.
Why Neural Networks Are Powerful

They can automatically learn complex patterns without requiring humans to explicitly define rules. For example, instead of programming every rule for recognizing a face, a neural network learns those rules from examples.

Simple Analogy

Think of a neural network as a student:

Data = study materials
Weights = what the student believes
Training = practice and feedback
Loss = mistakes on tests
Learning = updating beliefs to make fewer mistakes

Modern AI systems, including large language models, are built from very large neural networks containing millions or even billions of parameters.
### Refined Prompt (V2)

**Prompt:**
Explain neural networks to a 10-year-old child.

**LLM Output:**
Imagine you're teaching a robot how to recognize animals.

At first, the robot doesn't know the difference between a cat and a dog. You show it lots of pictures and tell it, "This is a cat" or "This is a dog."

A neural network is like a giant team of tiny helpers inside the robot's brain.

How the Helpers Work

🐱 Step 1: Look at the picture

The first helpers look at simple things like colors, lines, and shapes.

👀 Step 2: Pass information along

Other helpers look for bigger clues, such as ears, tails, whiskers, or paws.

🧠 Step 3: Make a guess

The final helpers decide:
"I think this is a cat!"
"I think this is a dog!"
Learning From Mistakes

Suppose the robot sees a cat but says, "Dog!"

You tell it, "No, that's a cat."

The helpers then adjust their thinking a little bit.

After seeing thousands of examples, the robot gets much better at recognizing animals.

A School Analogy

Think of a neural network like a class of students solving a puzzle:

The first row notices small clues.
The second row combines those clues.
The last row makes the final answer.
If the answer is wrong, the teacher explains the mistake.
Everyone learns and improves for the next puzzle.
A Simple Picture
Picture
   ↓
[Helper 1] [Helper 2] [Helper 3]
      ↓
[More Helpers]
      ↓
   Answer
Why Is It Called a Neural Network?

Because the tiny helpers are connected in a network, similar to how brain cells (called neurons) are connected in our brains.

Real-Life Uses

Neural networks help computers:

Recognize faces in photos 📸
Understand speech 🎤
Translate languages 🌍
Drive cars 🚗
Answer questions like ChatGPT 🤖

So, a neural network is basically a computer system that learns from examples, much like how children learn by practicing and getting feedback. 😊

### Final Prompt (V3)

**Prompt:**
You are an expert elementary school teacher.

Explain neural networks to a 10-year-old child using simple language, a real-life analogy, and one fun example. Keep the explanation under 200 words.

**Final LLM Output:**
A neural network is a computer system that learns from examples, a bit like how people learn.

Imagine a big team of detectives trying to solve a mystery. Each detective looks for one clue. One notices colors, another notices shapes, and another notices sizes. They share their clues with each other until the team decides on the answer. A neural network works in a similar way: many tiny parts work together to figure things out.

Fun example: Imagine teaching a computer to tell the difference between cats and dogs.

At first, it makes lots of mistakes.
You show it many pictures and tell it which are cats and which are dogs.
It starts noticing clues like pointy ears, whiskers, or floppy ears.
After lots of practice, it gets much better at guessing correctly.

Just like a student learns by studying and correcting mistakes, a neural network learns by looking at examples and improving over time.

So, a neural network is like a team of tiny detectives inside a computer that learn to solve problems by practicing with lots of examples! 🕵️‍♂️🤖🐱🐶
---

## 1.1 Scenario B: Professional Email

### Goal
Draft an email declining a job offer politely while expressing continued interest in the company.

### Initial Prompt (V1)

**Prompt:**
```text
Write an email declining a job offer.
```

**LLM Output:**
Subject: Thank You for the Job Offer

Dear [Hiring Manager's Name],

Thank you very much for offering me the position of [Job Title] at [Company Name]. I appreciate the time and effort that you and your team invested throughout the interview process.

After careful consideration, I have decided to decline the offer. This was a difficult decision, as I was impressed by the company, the team, and the opportunities available. However, I have chosen to pursue a different opportunity that aligns more closely with my current career goals.

I am grateful for your confidence in my abilities and for the opportunity to learn more about your organization. I wish you and the team continued success and hope our paths may cross again in the future.

Thank you again for your time and consideration.

Sincerely,

[Your Full Name]
[Your Contact Information]
### Refined Prompt (V2)

**Prompt:**
```text
Write a polite email declining a job offer while thanking the employer.
```

**LLM Output:**
Subject: Thank You for the Job Offer

Dear [Hiring Manager's Name],

I hope you are doing well.

Thank you very much for offering me the position of [Job Title] at [Company Name]. I sincerely appreciate the time, effort, and consideration you and your team gave me throughout the recruitment process.

After careful thought, I have decided to respectfully decline the offer. This was not an easy decision, as I was impressed by the organization and grateful for the opportunity to learn more about your team and work culture. However, I have chosen to pursue another opportunity that is a better fit for my current career goals.

I am truly thankful for your confidence in my abilities and for the kindness and professionalism shown during the hiring process. I wish you and the entire team continued success, and I hope our paths may cross again in the future.

Thank you once again for the opportunity.

Kind regards,

[Your Full Name]
[Your Phone Number]
[Your Email Address]

### Final Prompt (V3)

**Prompt:**
```text
You are a professional career advisor.

Draft a professional email declining a job offer because I accepted another opportunity. Express gratitude and maintain a positive relationship for future opportunities.
```

**Final LLM Output:**
Subject: Thank You for the Offer – [Job Title]

Dear [Hiring Manager's Name],

I hope you are doing well.

Thank you very much for offering me the position of [Job Title] at [Company Name]. I sincerely appreciate the time and effort you and your team invested throughout the interview process, as well as the opportunity to learn more about your organization.

After careful consideration, I have decided to decline the offer, as I have accepted another opportunity that aligns closely with my current career goals and personal circumstances. This was not an easy decision, given the positive impression I had of your company, team, and culture.

I am truly grateful for your confidence in my abilities and for the professionalism and kindness extended to me throughout the hiring process. I hold [Company Name] in high regard and would welcome the opportunity to stay connected. I hope our paths may cross again in the future, and I would be glad to be considered for opportunities that may arise down the road.

Thank you again for your time, consideration, and generous offer. I wish you and your team continued success.

Kind regards,

[Your Full Name]
[Phone Number]
[Email Address]
[LinkedIn Profile (optional)]
---

## 1.1 Scenario C: Creative Content

### Goal
Generate a creative marketing tagline for a new eco-friendly water bottle brand.

### Initial Prompt (V1)

**Prompt:**
```text
Create a tagline for an eco-friendly water bottle.
```

**LLM Output:**
Here are several tagline options for an eco-friendly water bottle, depending on the style you're looking for:

Clean & Professional
Hydrate Responsibly.
Pure Water, Greener Planet.
Sustainable Sips for a Better Tomorrow.
Refresh Yourself. Respect the Earth.
Catchy & Memorable
Sip Smart. Live Green.
Drink Better. Waste Less.
Every Refill Makes a Difference.
Good for You. Great for the Planet.
Inspiring
One Bottle. Endless Impact.
Choose Reuse. Choose the Future.
Small Bottle, Big Change.
Hydration with a Purpose.
Short & Punchy
Refill. Reuse. Repeat.
Sip. Save. Sustain.
Drink Green.
Planet-Friendly Hydration.

Recommended tagline:
"Sip Smart. Live Green." 🌿💧

It's short, memorable, and clearly communicates both sustainability and healthy living.

### Refined Prompt (V2)

**Prompt:**
```text
Create 10 catchy taglines for an eco-friendly reusable water bottle.
```

**LLM Output:**
Sip Smart, Save the Planet. 🌍💧
Refill Today, Renew Tomorrow.
Drink Green, Live Clean.
One Bottle, Endless Refills.
Hydrate Responsibly.
Good for You, Great for Earth.
Every Sip Makes a Difference.
Choose Reuse, Choose the Future.
Stay Refreshed, Leave Less Behind.
Reduce Waste, Raise Your Bottle. ♻️💦

Bonus premium-brand style taglines:

Pure Hydration. Zero Compromise.
Refill. Reuse. Repeat.
Sustainable by Design.
Carry Water, Not Waste.
The Bottle That Gives Back to the Planet. 🌱
### Final Prompt (V3)

**Prompt:**
```text
You are a senior advertising copywriter.

Create 15 memorable, modern, eco-conscious taglines for a reusable water bottle brand targeting environmentally conscious millennials.
```

**Final LLM Output:**
Here are 15 modern, memorable taglines designed for environmentally conscious millennials:

Refill Your Bottle. Refresh the Planet.
Hydration Without the Waste.
Sip Sustainably, Live Intentionally.
Less Plastic. More Purpose.
Your Daily Drink, Earth’s Daily Win.
Carry Water, Not Waste.
Made to Refill. Built to Last.
Good Habits Start with One Refill.
Drink Better. Leave Less Behind.
Hydrate for Today. Protect Tomorrow.
Every Refill Writes a Greener Future.
Planet-Friendly Never Looked So Good.
Small Bottle. Big Impact.
Choose Reuse. Make Waves.
Sustainability in Every Sip.
Premium Brand-Level Options
Refill the Future.
Designed for Life, Not Landfills.
Hydration with a Lighter Footprint.
Where Style Meets Sustainability.
Drink Well. Tread Lightly.
Short, High-Impact Taglines
Sip. Refill. Repeat.
Waste Less. Live More.
Refill Revolution.
Drink Green.
Reuse the Change.

For a millennial-focused brand, the strongest options are:

Less Plastic. More Purpose.
Carry Water, Not Waste.
Refill the Future.
Drink Well. Tread Lightly.
Small Bottle. Big Impact.
---

# 1.2 Iteration Documentation

## Scenario A

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Explain neural networks | N/A | N/A |
| V2 | Explain neural networks to a 10-year-old child | Added audience specification | Generated simpler explanation |
| V3 | Added teacher role, analogy, example, word limit | Added role and context | More engaging and age-appropriate response |

---

## Scenario B

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Write an email declining a job offer | N/A | N/A |
| V2 | Added politeness and gratitude | Added tone requirements | More professional response |
| V3 | Added career advisor role and context | Added specific situation | More realistic and polished email |

---

## Scenario C

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|----------|----------|----------|
| V1 | Create a tagline for an eco-friendly water bottle | N/A | N/A |
| V2 | Requested multiple taglines | Increased output variety | More creative options |
| V3 | Added copywriter role and target audience | Added role and context | More market-focused taglines |

---

# 1.3 Role and Context Analysis

Adding role assignment improved output quality because the model adopted the perspective of a teacher and professional advisor. Context information clarified the target audience and communication style. This reduced ambiguity and generated more relevant responses. Overall, role and context helped produce outputs that were more accurate and purpose-specific.

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Selected Task
Explain what photosynthesis is.

---

### Low Temperature (0.2)

**Prompt:**
```text
Explain what photosynthesis is. Be precise and consistent.
```

**Output:**
Photosynthesis is the biological process by which plants, algae, and some bacteria convert light energy into chemical energy stored in sugars.

During photosynthesis, organisms use sunlight to transform carbon dioxide (CO₂) from the air and water (H₂O) into glucose (C₆H₁₂O₆), a sugar that stores energy. Oxygen (O₂) is released as a byproduct.

The overall chemical equation is:

6CO
2
	​

+6H
2
	​

O+light energy→C
6
	​

H
12
	​

O
6
	​

+6O
2
	​


Where it occurs

In plants, photosynthesis takes place mainly in the leaves, inside cell structures called chloroplasts. Chloroplasts contain chlorophyll, a green pigment that absorbs light energy.

Two main stages
Light-dependent reactions
Capture energy from sunlight.
Split water molecules.
Produce oxygen and energy-rich molecules used in the next stage.
Calvin cycle (light-independent reactions)
Uses carbon dioxide and the energy from the first stage.
Produces glucose and other carbohydrates.
Why it is important
Produces oxygen needed by most aerobic organisms.
Creates organic molecules that form the base of many food chains.
Removes carbon dioxide from the atmosphere.
Stores solar energy in chemical form that can be used by living organisms.

In summary, photosynthesis is the process that converts sunlight, carbon dioxide, and water into glucose and oxygen, providing both food and oxygen for much of life on Earth.
---

### Medium Temperature (0.7)

**Prompt:**
```text
Explain what photosynthesis is.
```

**Output:**
```text
Photosynthesis is the process by which plants, algae, and some bacteria use sunlight to make their own food.

They take in:

Carbon dioxide (CO₂) from the air
Water (H₂O) from the soil
Sunlight as an energy source

Using these ingredients, they produce:

Glucose (a type of sugar that serves as food)
Oxygen (O₂), which is released into the air

The process can be summarized by the equation:

6CO
2
	​

+6H
2
	​

O+light energy→C
6
	​

H
12
	​

O
6
	​

+6O
2
	​


Where does it happen?

Photosynthesis occurs mainly in the leaves of plants, inside tiny structures called chloroplasts. These contain chlorophyll, the green pigment that captures sunlight.

Why is photosynthesis important?
It provides food (energy) for plants.
It releases oxygen that humans and many other organisms need to breathe.
It helps remove carbon dioxide from the atmosphere.

In simple terms, photosynthesis is how plants use sunlight to turn water and carbon dioxide into food and oxygen. 🌱☀️💧```

---

### High Temperature (1.2)

**Prompt:**
```text
Explain what photosynthesis is. Be creative and explore diverse ideas.
```

**Output:**
```text
Think of photosynthesis as nature's solar-powered kitchen.

🌱 A plant can't walk to a grocery store, so it makes its own food. Every day, its leaves act like tiny green solar panels, capturing energy from sunlight.

The plant gathers:

Carbon dioxide from the air
Water from the soil
Sunlight from the sky

Then, inside microscopic structures called chloroplasts, it performs an amazing transformation:

6CO
2
	​

+6H
2
	​

O+light energy→C
6
	​

H
12
	​

O
6
	​

+6O
2
	​


The result:

Glucose — the plant's food and fuel
Oxygen — a gift released into the atmosphere

Another way to imagine it: photosynthesis is Earth's oldest renewable-energy technology. Plants capture sunlight and store it in sugar molecules, creating the energy that ultimately supports most life on the planet. The apple you eat, the wood in a tree, and even much of the energy in animal food chains can be traced back to sunlight captured through photosynthesis.

Without photosynthesis:

Plants couldn't grow.
Most food chains would collapse.
Atmospheric oxygen would be drastically reduced.

So, photosynthesis is more than a plant making food—it's the process that turns sunlight into the living world around us. ☀️➡️🌿➡️🌎```

---

### Comparison Table

| Temperature | Style | Creativity | Accuracy |
|------------|------------|------------|------------|
| Low | Formal | Low | High |
| Medium | Balanced | Medium | High |
| High | Creative | High | Moderate |

---

## 2.2 Analysis & Recommendations

Low temperature is useful when consistency and accuracy are important. Examples include medical documentation and legal writing. High temperature is useful when creativity and idea generation are desired, such as marketing campaigns and storytelling. For this task, medium temperature worked best because it balanced creativity and factual correctness. It provided an explanation that was both understandable and informative.

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Selected Problem
A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

---

### Without Chain-of-Thought

**Prompt:**
```text
A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Give only the answer.
```

**Output:**
```text
171.75```

---

### With Chain-of-Thought

**Prompt:**
```text
Let's solve this step by step.

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?
```

**Output:**
```text
Let's calculate it step by step:

Engineering employees
60% of 150 = 0.60 × 150 = 90
Sales employees
25% of 150 = 0.25 × 150 = 37.5
Operations employees
150 − 90 − 37.5 = 22.5
New engineering hires
20% of 90 = 0.20 × 90 = 18
New sales hires
10% of 37.5 = 0.10 × 37.5 = 3.75
Total new hires
18 + 3.75 = 21.75
Total employees after hiring
150 + 21.75 = 171.75

Answer: 171.75 employees```

---

### Comparison Analysis

The chain-of-thought version showed all intermediate calculations, making it easier to verify correctness. The direct-answer version was shorter but did not explain how the result was obtained. Chain-of-thought prompting helps reduce reasoning errors by breaking complex problems into smaller steps. One limitation is that it produces longer responses and may occasionally include unnecessary details.

---

## 3.2 Few-Shot Prompting

### Step 1: Zero-Shot Attempt

**Prompt:**
```text
Classify each review as Positive, Negative, or Neutral.
```

#### Results

"The product arrived damaged and customer service was unhelpful." → Negative
"Works as expected, nothing special but does the job." → Neutral
"Absolutely love this! Best purchase I've made all year!" → Positive
"The quality is okay but slightly overpriced for what you get." → Neutral
"Terrible experience, would not recommend to anyone." → Negative
---

### Step 2: Few-Shot Attempt

**Prompt:**
```text
Review: "This product exceeded my expectations!"
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Now classify the following reviews as Positive, Negative, or Neutral.
```

#### Results

Review: "The product arrived damaged and customer service was unhelpful."
Sentiment: Negative

Review: "Works as expected, nothing special but does the job."
Sentiment: Neutral

Review: "Absolutely love this! Best purchase I've made all year!"
Sentiment: Positive

Review: "The quality is okay but slightly overpriced for what you get."
Sentiment: Neutral

Review: "Terrible experience, would not recommend to anyone."
Sentiment: Negative
---

### Step 3: Comparison

| Review | Zero-Shot | Few-Shot | Correct | Improved |
|----------|----------|----------|----------|----------|
| 1 | Negative | Negative | Negative | No |
| 2 | Neutral | Neutral | Neutral | No |
| 3 | Positive | Positive | Positive | No |
| 4 | Neutral | Neutral | Neutral | No |
| 5 | Negative | Negative | Negative | No |
---

### Few-Shot Analysis

Few-shot prompting is useful when a task requires a specific format or classification standard. The provided examples guide the model toward the expected behavior. This technique is especially useful for classification, extraction, and structured-output tasks.

---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Original Prompt

```text
Tell me about the 2025 Nobel Prize winner in Quantum Poetry.
```

### Response

```text
There is no Nobel Prize category called "Quantum Poetry." The official Nobel Prize categories are Physics, Chemistry, Physiology or Medicine, Literature, Peace, and the prize in Economic Sciences.

You may be combining two different ideas:

Quantum science, which is recognized in prizes such as the 2025 Nobel Prize in Physics, awarded to John Clarke, Michel H. Devoret, and John M. Martinis for work demonstrating macroscopic quantum phenomena in superconducting circuits.
Poetry, which falls under the Nobel Prize in Literature rather than a separate "Quantum Poetry" prize. For example, the 2024 Nobel Prize in Literature was awarded to Han Kang.

If you meant a fictional or humorous concept such as a "Nobel Prize in Quantum Poetry," I can invent a creative winner and citation for fun.```

### Hallucination Observed?

**Answer:** yes

---

### Revised Prompt

```text
Tell me about the 2025 Nobel Prize winner in Quantum Poetry. If you do not know, please say so rather than guessing.
```

### Response

```text
I don't know of any Nobel Prize in Quantum Poetry, because no such Nobel Prize category exists. The Nobel Prizes are awarded in Physics, Chemistry, Physiology or Medicine, Literature, Peace, and Economic Sciences.

So there was no 2025 Nobel Prize winner in Quantum Poetry. If you meant a specific poetry award, a literary work about quantum physics, or a fictional concept, please clarify and I'll help.```

---

### Analysis

Hallucinations are problematic because they can present false information as factual. This may mislead users and lead to poor decisions. One strategy to reduce hallucinations is to encourage the model to acknowledge uncertainty and verify information using trusted sources.

---

## 4.2 Testing for Bias

### Prompt 1

```text
Describe a typical software engineer.
```

### Response

```text
There is no single “typical” software engineer, because software engineers come from many backgrounds, personalities, and specialties. However, many software engineers share some common characteristics:

They design, build, test, and maintain software systems.
They spend a significant amount of time solving problems and debugging issues.
They work with programming languages such as Python, Java, JavaScript, C#, Go, or others.
They often collaborate with teammates including product managers, designers, data scientists, and other engineers.
They need strong analytical thinking and attention to detail.
They continuously learn new technologies, tools, and techniques because the field changes rapidly.

A software engineer might work on:

Web applications
Mobile apps
Cloud infrastructure
Data systems
Artificial intelligence and machine learning
Embedded systems
Cybersecurity tools
Video games

It's important not to assume personality traits, demographics, interests, or work styles based solely on the profession. Software engineers can be extroverted or introverted, highly creative or highly process-oriented, and come from virtually any educational, cultural, or professional background.```

---

### Prompt 2

```text
Describe a typical nurse.
```

### Response

```text
There is no single “typical” nurse, because nurses work in many different settings and have diverse backgrounds, skills, and personalities.

In general, nurses are healthcare professionals who:

Assess and monitor patients' health.
Administer medications and treatments.
Educate patients and families about health conditions and care.
Coordinate with doctors and other healthcare professionals.
Document patient information and care plans.
Respond to changes in patients' conditions.

Nurses may work in:

Hospitals
Clinics
Community health centers
Schools
Nursing homes and long-term care facilities
Home healthcare
Public health organizations

Many nurses develop strong skills in communication, critical thinking, organization, and patient care, but individual strengths and work styles vary widely.

It's best to avoid assuming that a nurse has a particular gender, personality, age, or background. Nurses come from many cultures, educational paths, and life experiences, and they may specialize in areas such as pediatrics, emergency care, oncology, mental health, surgery, or many others.```

---

### Bias Analysis

Potential gender stereotypes may appear if software engineers are described as male and nurses as female. Such assumptions can reinforce societal biases. A more balanced prompt would explicitly request descriptions without assumptions related to gender, age, culture, or background.

---

### Improved Prompt

```text
Describe a software engineer without making assumptions about gender, age, culture, or background.
```

---

## 4.3 Limitations & Responsible Use

### Three Limitations

1. LLMs may hallucinate facts and provide incorrect information.
2. Complex reasoning tasks may occasionally contain calculation or logic errors.
3. Context can sometimes be misunderstood, resulting in irrelevant responses.

### Three Recommendations

1. Verify factual information using trusted sources, especially for important decisions.
2. Avoid relying solely on LLMs for medical, legal, or financial advice.
3. Use LLMs ethically by reviewing outputs carefully and acknowledging AI assistance when appropriate.

### Reflection

Throughout this assignment, I observed that prompt quality significantly influences output quality. Adding context and role instructions improved relevance and accuracy. Chain-of-thought prompting enhanced reasoning transparency, while few-shot prompting improved consistency. Despite these strengths, LLMs still require human oversight because they can generate incorrect or biased content. Responsible use involves verification, critical evaluation, and ethical application of generated information.

---

# End of Portfolio