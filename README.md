# FDP-TCET
## 1. BE Specfic :
If you ask a vague question, you may get a vague answer. The more details you provide, the better the model can give you what you're looking for

Instead of : 
```
Tell me about all dog breeds that exist ?
```

Ask :
```
What are the different breeds of dog for small aparment living ?
```

## 2. State Your Intent :
Make your purpose clear in your question. Specify why you are asking or what you hope to achieve. For instance, instead of simply requesting

Instead of : 
```
Explain quantum physics ?
```

Ask :
```
I'm helping my college-grade student with his Physics homework. Could you explain quantum physics in a simple way?
```

## 3. Use Correct Spelling and Grammar: 
Although ChatGPT can handle some spelling and grammar issues, it's best to provide clear and well-structured prompts. This ensures you receive accurate responses.

## 4. Direct the Output Format:
If you have a specific format in mind for the response, mention it in your question.

Instead of :
```
Could you list the steps to make a NOR gate?
```
Ask for : 
```
Could you explain the process of making a NOR gate in tabular form?
```
## 5. Ask Follow- Up questions: 
If ChatGPT's response doesn't fully address your query or if you need more information, don't hesitate to ask follow-up 

## 6. Experiment with Different Phrasings:
If you're not getting the desired response, try rephrasing your question. Different wording may lead to a better understanding of your intent.

## 7. Prompt for Fact-Checking: 
When seeking reliable information, you can request ChatGPT to provide sources or fact-check information. 

Ask For : 
```
Can you fact-check this statement: The tallest mountain in the world is Mount Everest?
```

## Here is the formula for a perfect prompt.
### [Context] + [Specific Information] + [Intent/Goal] + [Response Format (if needed)] = Perfect Prompt

### Example 1 :
- Context: "I'm a software developer"
- Specific Information: "working on a Python project"
- Intent/Goal: "Can you explain how to implement exception handling in Python?"
- Response Format (if needed): Write it in a simple paragraph or list.

Perfect Prompt: 
```
I'm a software developer working on a Python project. Can you explain how to implement exception handling in Python? Write it in a simple paragraph or list.
```

### Example 2 :
- Context: "I'm a Engineering Professor"
- Specific Information: "working on making MCQs for class test"
- Intent/Goal: "Can you make MCQs on the basis of syllabus given in <>"
- Response Format (if needed): Write it into tabular form.

Perfect Prompt: 
```
I'm a Engineering Professor working on making MCQs for class test.Can you make MCQs on the basis of syllabus given in <>.Write it into tabular form.
```

## AIPRM (Artificial Intelligence-Powered Response Manager)
### Generating our Own Prompt :
#### Example 1 :
Prompt Template:
```
Please act as a professor and create 10 multiple-choice questions (MCQs) with varying levels of difficulty based on the provided syllabus. The syllabus covers topics in advanced Engineering.  Ensure that the questions are specific, well-structured, and assess various aspects of the subject matter. Please provide four answer choices for each question, with only one correct answer. Additionally, accompany each question with a brief explanation or context to help students understand the concept being tested.[TARGETLANGUAGE]. The provided syllabus is :

[PROMPT]
```

#### Example 2 :
Prompt Template:
```
Create a PowerPoint presentation content on the topic  given below. Your presentation should consist of 10 slides . Each slide should have a concise title and bullet points summarizing the main ideas. Additionally, provide speaker notes for each slide explaining the content in more detail. Ensure that your presentation is informative and engaging.[TARGETLANGUAGE]. The topic is 


[PROMPT]
```
