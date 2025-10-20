# Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

# Date: 21/10/2025
# Register no. 25000527
# Aim:
To write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights using prompt-based programming.
________________________________________
# AI Tools Required:
•	OpenAI GPT-4 / ChatGPT – for prompt-based code generation and summarization.
•	Google Gemini / Copilot / Claude – for cross-verification and code refinement.
•	External APIs – e.g., OpenWeatherMap or WeatherAPI (for demonstration).
•	Python Libraries: requests, json, pandas (optional).
________________________________________
Explanation:
This experiment demonstrates how prompt engineering and AI-assisted coding can help automate real-world programming tasks such as:
•	Fetching and comparing data from multiple APIs.
•	Generating Python code via LLMs.
•	Extracting actionable insights automatically.
Students act as AI-assisted programmers, using prompts to instruct the AI tools to generate code for a specific use case and analyze the results.
________________________________________
# Procedure:
Step 1: Define Scenario
Use Case – Weather Data Comparison and Insight Generation
The application fetches current weather data (temperature, humidity, and condition) from two different APIs and compares their outputs.
________________________________________
Step 2: Design Prompts
1.	Prompt 1 – Code Generation:
“Write Python code to fetch current weather data (temperature, humidity, condition) from OpenWeatherMap and WeatherAPI using their REST APIs.”
2.	Prompt 2 – Data Comparison:
“Modify the code to compare both API outputs and print which API gives the higher temperature.”
3.	Prompt 3 – Insight Generation:
“Based on the comparison, generate a short summary explaining any difference and suggest which API data seems more reliable.”
Step 3: Python Implementation Example
import requests

# API URLs (example placeholders)
api1 = "https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric"
api2 = "https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=London"

# Fetch data from both APIs
data1 = requests.get(api1).json()
data2 = requests.get(api2).json()

# Extract relevant details
temp1 = data1['main']['temp']
humidity1 = data1['main']['humidity']
temp2 = data2['current']['temp_c']
humidity2 = data2['current']['humidity']

# Compare results
print(f"OpenWeatherMap Temperature: {temp1}°C | Humidity: {humidity1}%")
print(f"WeatherAPI Temperature: {temp2}°C | Humidity: {humidity2}%")

# Generate insight
if temp1 > temp2:
    print("Insight: OpenWeatherMap shows slightly warmer data, possibly due to recent updates.")
elif temp2 > temp1:
    print("Insight: WeatherAPI reports a higher temperature; may indicate real-time precision.")
else:
    print("Insight: Both APIs report consistent temperature readings.")


Step 4: Execution Across AI Tools
•	The above code was generated using ChatGPT and cross-verified with Gemini and Copilot.
•	Gemini provided a slightly more modular version using functions.
•	Copilot offered inline documentation and variable suggestions automatically.
________________________________________
Step 5: Evaluation Criteria
Each AI tool’s performance was compared using the following rubrics:
Criterion	ChatGPT	Gemini	Copilot
Code Accuracy	✅ Excellent	✅ Good	✅ Good
Readability	✅ Excellent	✅ Excellent	✅ Excellent
API Integration	✅ Supported	⚠️ Needs minor edits	✅ Supported
Insight Explanation	✅ Detailed	✅ Moderate	⚠️ Minimal
________________________________________
Output:
Example console output for London:
OpenWeatherMap Temperature: 15.3°C | Humidity: 60%
WeatherAPI Temperature: 14.8°C | Humidity: 62%
Insight: OpenWeatherMap shows slightly warmer data, possibly due to recent updates.
________________________________________
Reflection:
This experiment demonstrated the effectiveness of prompt-based code generation.
•	ChatGPT generated clean, runnable code on the first attempt.
•	Gemini produced modular but less optimized syntax.
•	Copilot helped with inline completions but lacked contextual summaries.
By refining prompts (adding constraints like “use comments,” “compare outputs numerically,” etc.), output quality improved.
This proved that prompt clarity and specificity directly influence AI code quality and interpretability.
________________________________________
# Result:
The corresponding prompts were executed successfully, and the AI-generated code produced accurate results with meaningful insights.

