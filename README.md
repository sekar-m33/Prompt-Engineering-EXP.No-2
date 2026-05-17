# EX-02: Cross-Platform Prompting – Evaluating Diverse Techniques in AI-Powered Text Summarization
## AIM :

To evaluate and compare the effectiveness of different prompting techniques (Zero-shot, Few-shot, Chain-of-Thought, and Role-based prompting) across multiple AI platforms such as OpenAI ChatGPT, Google Gemini, Anthropic Claude, and Microsoft Copilot for the task of text summarization.

## SCENARIO :

A content curation team for an educational platform needs short and simple summaries of technical research papers for undergraduate students. A 500-word article on “The Basics of Blockchain Technology” is summarized using different prompting strategies on multiple AI platforms.

### The summaries are evaluated based on :

Accuracy
Coherence
Simplicity
Speed
User Experience
## PROMPTING TECHNIQUES USED
### 1. Zero-Shot Prompting

The AI is directly asked to summarize without examples.

Example Prompt:
“Summarize the following article on Blockchain Technology in simple language for undergraduate students.”

### 2. Few-Shot Prompting

The AI is first given sample summaries and then asked to summarize the new article.

Example Prompt:
“Here are two examples of good summaries. Now summarize the blockchain article in a similar format.”

### 3. Chain-of-Thought Prompting

The AI is encouraged to reason step-by-step before generating the summary.

Example Prompt:
“Read the article carefully, identify the key concepts, simplify them step-by-step, and then provide a concise summary.”

### 4. Role-Based Prompting

The AI is assigned a specific role before answering.

Example Prompt:
“You are an educational content writer preparing notes for first-year engineering students. Summarize the blockchain article in simple terms.”

## SAMPLE ARTICLE SUMMARY GENERATED
### Summary

Blockchain is a decentralized digital ledger used to securely record transactions across multiple computers. Each block contains transaction data and is connected to previous blocks using cryptographic techniques, making the system secure and difficult to alter. Blockchain technology is widely used in cryptocurrencies like Bitcoin, but it also has applications in healthcare, banking, and supply chain management. Its advantages include transparency, security, and decentralization, while challenges include high energy consumption and scalability issues.

## COMPARISON OF AI PLATFORMS
| Platform          | Accuracy  | Coherence | Simplicity | Speed     | User Experience         |
| ----------------- | --------- | --------- | ---------- | --------- | ----------------------- |
| OpenAI ChatGPT    | Excellent | Excellent | Excellent  | Fast      | Very User Friendly      |
| Google Gemini     | Very Good | Good      | Good       | Very Fast | Good                    |
| Anthropic Claude  | Excellent | Excellent | Very Good  | Moderate  | Clean Interface         |
| Microsoft Copilot | Good      | Good      | Moderate   | Fast      | Integrated with Browser |

## ANALYSIS OF PROMPTING TECHNIQUES
| Prompting Technique | Advantages                          | Disadvantages              |
| ------------------- | ----------------------------------- | -------------------------- |
| Zero-Shot           | Quick and simple                    | May miss important details |
| Few-Shot            | Better formatting and consistency   | Requires example prompts   |
| Chain-of-Thought    | Produces detailed logical summaries | Slightly slower            |
| Role-Based          | More audience-focused and readable  | Depends on role clarity    |

## OBSERVATIONS :
Role-based prompting produced the most student-friendly summaries.
Chain-of-thought prompting improved logical flow and coherence.
Few-shot prompting improved formatting consistency.
Zero-shot prompting was the fastest but less detailed.
ChatGPT and Claude produced the most accurate and coherent summaries overall.
Gemini responded very quickly with concise outputs.
Copilot worked efficiently for web-based summarization tasks.

## RESULT :
The experiment showed that both the AI platform and prompting strategy significantly affect the quality of text summarization.

### Among the tested combinations:

ChatGPT with Role-Based Prompting produced the best overall summary because it balanced accuracy, simplicity, coherence, and readability for undergraduate students.
Claude with Chain-of-Thought Prompting generated highly detailed and logically structured summaries.
Gemini provided the fastest responses.
Copilot offered a convenient browser-integrated experience.

Therefore, Role-Based Prompting combined with ChatGPT was found to be the most effective approach for educational text summarization tasks.
