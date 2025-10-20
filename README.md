# Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

# Date: 21/10/2025
# Register no. 25000527
# Aim: Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools

# AI Tools Required
•	OpenAI GPT-4 / ChatGPT – for text interpretation, summarization, and insight generation
•	Anthropic Claude – for comparative text generation and evaluation
•	Google Gemini / Copilot – for alternate text generation and contextual reasoning
•	Optional Output Analysis: JSON for structured storage, Pandas or Excel for tabular comparison
________________________________________
# Use Case
Scenario:
Develop a system that automatically interacts with multiple AI tools (e.g., ChatGPT, Claude, Gemini) to perform prompt-based text generation, compare their outputs, and extract actionable insights from those comparisons.
Example Application:
A programmer persona is tasked to design a simple “Online Bookstore Management System” using multiple AI tools. Each tool is prompted to generate code, documentation, and improvement suggestions.
The experiment aims to:
•	Automate API interaction with multiple AI tools.
•	Collect and compare text/code outputs.
•	Evaluate them using qualitative metrics.
•	Summarize the most accurate or useful result.
________________________________________
# Objective
To develop a comparative AI evaluation framework that:
•	Interacts with multiple AI APIs via prompt automation.
•	Collects responses to a uniform prompt (“Act as a programmer; design a bookstore system”).
•	Compares quality, readability, and completeness.
•	Generates structured insights and recommendations.
________________________________________
# Procedure
Step 1: Define the Use Case
A persona-based prompt (“Act as a programmer...”) is used to make each AI generate an application design.
Goal: Identify which AI produces the most coherent, technically accurate, and complete response.
Step 2: Set Up API Access
Securely configure and authenticate APIs for each tool (OpenAI, Anthropic, Gemini, etc.) using environment variables.
Each model will receive the same input prompt for fair comparison.
Step 3: Prompt Execution
For each AI tool:
1.	Send the same standardized prompt.
2.	Collect text or code output.
3.	Record response metadata (tokens, latency, etc.).
Step 4: Output Comparison
Compare outputs based on:
•	Accuracy (technical correctness)
•	Completeness (all major features included)
•	Readability (clarity, structure)
•	Creativity (novel ideas, design choices)
Step 5: Evaluation Method
Use a simple rubric-based evaluation (e.g., 1–5 scale per metric).
Optionally, compute basic similarity metrics like text overlap or keyword matching.
Criteria	Description	Score (1–5)
Accuracy	Technical correctness	4
Completeness	Coverage of features	5
Readability	Clarity and formatting	4
Creativity	Originality	3
Step 6: Generate Actionable Insights
Summarize which tool performed best overall and note improvement areas.
Output structured as:
•	Best performing AI: (e.g., ChatGPT)
•	Reasons: Concise, accurate, user-friendly responses.
•	Recommendation: Use GPT for detailed technical explanations; use Claude for creative ideation.
________________________________________
# Output
•	Structured table of AI responses and scores
•	JSON or CSV summary of results
•	Natural language report (e.g., “GPT provided the most structured code; Claude gave more innovative design suggestions.”)
________________________________________

# Result: The corresponding Prompt is executed successfully.
