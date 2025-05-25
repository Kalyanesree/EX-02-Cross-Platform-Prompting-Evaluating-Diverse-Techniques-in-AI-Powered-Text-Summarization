# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
# REGISTER NO: 212222050028          # NAME: KALYANE SREE M

# Aim:
To evaluate and compare the effectiveness of prompting techniques-Zero-shot, Few-shot, Chain-of­ Thought (CoT), and Role-based prompting-across different Al platforms (ChatGPT, Claude, Gemini, Copilot) for a common task: summarizing a 500-word technical article on "The Basics of Blockchain Technology".

# Scenario:

A content curation task is considered where an educational platform requires concise, student-friendly summaries of complex research articles. For this study, a 500-word technical article titled "The Basics of Blockchain Technology" is used as the source text. Summaries are generated using various prompting strategies across different Al platforms to analyze performance based on the following criteria:
Accuracy (factual correctness and inclusion of key points) Coherence (logical flow and readability)
Simplicity (ease of understanding for undergraduate students) Speed (time taken to generate response)
User Experience (ease of use, interface quality)

# Algorithm: 

# Selection of Platforms:

ChatGPT (OpenAI) Gemini (Google)
 
Claude (Anthropic)

Microsoft Copilot (via Edge or Word)

# Prompting Techniques:

# Zero-shot prompting:
A direct request for summary without any example.

# Few-shot prompting: 
Includes 1-2 examples of a summarized text before the actual prompt. Chain-of-Thought prompting: Encourages reasoning steps before summarization.
# Role-based prompting:
Assigns a role to the model, such as "Act like an educator summarizing for undergraduates."

# Steps:

Prepare a uniform input article: The Basics of Blockchain Technology (~500 words). Apply each prompting technique across all selected Al platforms.
Record summaries, response time, and user experience notes.

Evaluate each output based on predefined rubrics for accuracy, coherence, simplicity, and overall clarity.
# Sample Prompts:

Zero-shot: "Summarize the following article for undergraduate students."

Few-shot: "Here's how a similar article was summarized: [example]. Now summarize this one." Chain-of-thought: "Explain the key components of the article step-by-step before summarizing it."
Role-based: "You are a college professor. Summarize this article in simple language for your students."

# Result:

The study revealed notable differences in the performance of prompting techniques across various Al platforms in terms of accuracy, coherence, simplicity, speed, and user experience.

On ChatGPT, the role-based prompting technique produced the most effective summary. The model, when instructed to act as a professor simplifying content for undergraduates, delivered a highly accurate and coherent summary. The explanation was both clear and contextually rich, making it easy for students to understand. Response time was fast, and the user interface was intuitive, providing an overall excellent experience.
 
On Claude, the chain-of-thought prompting produced a detailed summary by first breaking down key components like the definition of blockchain, its structure, and its applications. This made the summary high in accuracy, but slightly lower in coherence due to its segmented reasoning style. While the output was informative, it took slightly longer to generate, and the platform required more careful prompt phrasing to get optimal results.
Gemini performed well with the few-shot prompting technique. By providing 1-2 examples of well­ written summaries, the model was able to mimic a concise and student-friendly summarization style. It showed high coherence and simplicity, making the summary approachable for undergraduate readers. The response was generated quickly, and the overall user experience was smooth, with a well­ structured output.
Microsoft Copilot, using the zero-shot prompting technique, yielded moderate performance. While it responded quickly and without the need for examples or roles, the summaries lacked depth and occasionally omitted key technical aspects of blockchain. The structure was readable, but the explanation was more generic, making it less helpful for academic purposes. The interface was simple but limited in customization.

          


