# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Algorithm

4. ALGORITHM:

  ## 1)Access AI Platforms:
       Establish access to the specified AI platforms.

  ## 2)Prepare Prompts:
       For each AI platform, apply the four different prompt templates (zero-shot, few-shot, chain-of-thought, role-based) to the provided "The Basics of Blockchain Technology" article. Ensure consistent application of the prompt templates across all platforms.
   
  ## 3)Generate Summaries: 
       Instruct each AI platform to generate a summary based on each of the applied prompts.
       
  ## 4)Record Outputs: 
       Carefully record the generated summary text, the time taken for generation (speed), and any observations regarding the ease of use of the platform (user experience) for each combination of platform and prompt.
       
  ## 5)Evaluate Summaries: 
       Two independent human evaluators (from the content curation team) will assess each generated summary using the predefined evaluation rubric (Table 1) for accuracy, coherence, and simplicity. The average score from the two evaluators will be used for each criterion.
       
  ## 6)Data Analysis:
       *Calculate the average scores for accuracy, coherence, and simplicity for each combination of prompting technique and AI platform.
       *Compare the generation speed across different platforms and prompting techniques.
       *Analyze the subjective user experience ratings for each platform.
       *Identify the combination(s) of prompting technique and AI platform that yield the highest scores across the key evaluation criteria (accuracy, coherence, simplicity) while also considering speed and user experience.

## MATERIALS:

Source Text: A 500-word technical article titled "The Basics of Blockchain Technology" (attached as Appendix A).

AI Platforms: Access to the following AI platforms (via their respective APIs or interfaces):

ChatGPT (Specify version used, e.g., GPT-3.5, GPT-4)
Gemini (Specify version used, e.g., Gemini Pro, Gemini Ultra)
Claude (Specify version used, e.g., Claude 2, Claude 3)
Copilot (Specify the underlying model if known)
Prompt Templates: Standardized prompt templates for each prompting technique:

Zero-Shot: "Summarize the following technical article on 'The Basics of Blockchain Technology' for undergraduate students:" [ARTICLE TEXT]
Few-Shot: Development of 3-5 example input-summary pairs of similar technical content (around 100-150 words original, 30-50 words summary, tailored for undergraduate understanding). The prompt will be: "Below are a few examples of technical article summaries for undergraduate students. Please summarize the following article on 'The Basics of Blockchain Technology' in a similar style and level of detail:" [EXAMPLES] [ARTICLE TEXT]
Chain-of-Thought: Prompts designed to encourage step-by-step reasoning:
"Explain the core concepts of blockchain technology step by step, and then provide a concise summary suitable for undergraduate students based on the following article:" [ARTICLE TEXT]
(Optional) Few-shot examples demonstrating the chain-of-thought process followed by a concise summary.
Role-Based: Prompts instructing the AI to adopt a specific persona:
"Act as a knowledgeable tutor explaining blockchain technology to undergraduate students and provide a brief summary of the following article:" [ARTICLE TEXT]
"Summarize the key aspects of the following article on blockchain technology as if you were creating a quick study guide for undergraduate students:" [ARTICLE TEXT]
Evaluation Rubric: A predefined rubric (Table 1) for evaluating the generated summaries based on the following criteria:

Table 1: Summary Evaluation Rubric

| Criterion   | Description                                                                                                | Rating Scale (1-5, where 5 is best) |
| :---------- | :--------------------------------------------------------------------------------------------------------- | :---------------------------------- |
| Accuracy | The extent to which the summary accurately reflects the information presented in the original article.        | 1 (Very Inaccurate) - 5 (Completely Accurate) |
| Coherence | The logical flow and organization of ideas within the summary.                                               | 1 (Very Disjointed) - 5 (Highly Coherent) |
| Simplicity| The clarity and ease of understanding of the language used in the summary for an undergraduate audience. | 1 (Very Complex) - 5 (Very Simple) |
| Speed | The time taken by the AI platform to generate the summary (measured in seconds).                             | (Recorded in seconds)               |
| User Experience | Subjective assessment of the ease of interacting with the platform and obtaining the summary.             | 1 (Very Difficult) - 5 (Very Easy)    |

Stopwatch or Time Tracking Tool: For measuring the time taken for summary generation.

Data Recording Sheet: For logging the generated summaries, evaluation scores, and generation times for each platform and prompt combination.


Example Result Table (Illustrative):

Platform	Prompt Type	Summary (See Appendix B)	Accuracy (Avg.)	Coherence (Avg.)	Simplicity (Avg.)	Speed (seconds)	User Experience (Rating)
ChatGPT	Zero-Shot	...	4.2	3.8	3.5	5.1	4
ChatGPT	Few-Shot	...	4.5	4.1	4.0	6.8	4
ChatGPT	Chain-of-Thought	...	4.0	4.3	3.2	8.5	3
ChatGPT	Role-Based	...	4.3	3.9	3.8	5.5	4
Gemini	Zero-Shot	...	...	...	...	...	...
...	...	...	...	...	...	...	...

Export to Sheets
## CONCLUSION 
    This section will summarize the findings of the experiment, highlighting the most effective prompting techniques for text summarization on each AI platform based on the evaluation criteria. It will also discuss any observed trends, limitations of the experiment, and recommendations for the content curation team.

## APPENDIX:
    Appendix A: The 500-word technical article "The Basics of Blockchain Technology."
    Appendix B: The generated summaries for each platform and prompt combination.


## Result
    This section will contain the tabulated results of the evaluation, including the generated summaries (potentially in an appendix), the scores for each criterion for each platform and prompt combination, the recorded generation times, and qualitative observations on user experience.


