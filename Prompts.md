Prompt Library

### Experiment 1: Professional Email Writing

### Basic Prompt

Write an email to HR asking about a job vacancy.

### Basic Prompt Output

I am writing to inquire about any current job openings suitable for a fresher in Business Analytics, Data Analytics, or Business Analyst roles. I have completed my MBA in Business Analytics and am eager to begin my career and contribute to your organization.

Please let me know if there are any suitable opportunities available. I would be happy to share my resume for your consideration.

Thank you for your time.

### Improved Prompt

You are a professional recruitment communication assistant. Write an email to an HR recruiter asking about entry-level Prompt Engineering or Generative AI vacancies. The candidate has an MBA in Business Analytics and has completed analytics projects. Use a professional and confident tone. Do not invent work experience, certifications, or skills. Include a subject line and keep the email under 100 words.

### Improved Prompt Output

Dear HR Team,

I am writing to inquire about entry-level opportunities in Prompt Engineering or Generative AI at your organization. I have completed my MBA in Business Analytics and have worked on analytics projects as part of my academic journey.

I am eager to learn, develop my skills, and contribute to your team. I would appreciate it if you could let me know about any suitable openings.

Thank you for your time and consideration. I look forward to hearing from you.

Best regards,  
Rufina G.

### Results
 
 The basic prompt generated a general job inquiry email focused on Business Analytics and Data Analytics opportunities. The improved prompt generated a more targeted email asking about Prompt Engineering and Generative AI opportunities, with a professional tone and a subject line.

The improved prompt provided clearer instructions and better control over the email's purpose and format.

**Conclusion:** Adding context, specific instructions, and formatting requirements can help produce more relevant and structured AI responses. 

Experiment 2: Business Report Summarization

### Basic Prompt

Summarize this business report: Revenue increased from ₹5 lakh in January to ₹6 lakh in February. Customer complaints increased from 20 to 30. The company hired two new employees in February.

### Basic Prompt output
Revenue increased from ₹5 lakh in January to ₹6 lakh in February, reflecting a 20% growth. However, customer complaints also rose from 20 to 30, indicating a need to improve customer satisfaction. The company hired two new employees in February to support its operations.

### Improved Prompt

Act as a business analyst. Summarize the following report in three bullet points. Include the revenue change in rupees and percentage, the change in customer complaints, and the hiring update. Do not assume why any change occurred. Report: Revenue increased from ₹5 lakh in January to ₹6 lakh in February. Customer complaints increased from 20 to 30. The company hired two new employees in February.

### Improved Prompt Output
- Revenue Growth: Revenue increased from ₹5 lakh in January to ₹6 lakh in February, a rise of ₹1 lakh or 20%.
- Customer Complaints: Customer complaints increased from 20 in January to 30 in February, an increase of 10 complaints (50%).
- Hiring Update: The company hired two new employees in February.

### Results
The basic prompt produced a summary but included an unsupported assumption about improving customer satisfaction. The improved prompt instructed the AI to use exactly three bullet points, calculate the revenue percentage change, and avoid assuming reasons for changes.

The improved prompt is more specific and provides clearer output requirements.

Conclusion: Clear instructions can improve the accuracy and structure of business report summaries.

Experiment 3: Job Description Skill Extraction

### Basic Prompt

Find the skills in this job description: We need an analyst who can use Excel, SQL, Power BI, and Python to prepare reports, analyze data, and communicate insights to business teams.

### Basic Prompt output
Skills extracted:
- Excel
- SQL
- Power BI
- Python
- Report Preparation
- Data Analysis
- Insight Communication
- Business Communication

### Improved Prompt

Act as a recruitment analyst. Extract skills explicitly mentioned in the job description below. Return a table with two columns: Technical Skills and Business Skills. Do not add skills that are not mentioned. If a category has no skills, write None. Job description: We need an analyst who can use Excel, SQL, Power BI, and Python to prepare reports, analyze data, and communicate insights to business teams.

### Improved Prompt Output

| Technical Skills | Business Skills        |
| ---------------- | ---------------------- |
| Excel            | Report Preparation     |
| SQL              | Data Analysis          |
| Power BI         | Communicating Insights |

\| Python | None

### Results
The basic prompt extracted the skills from the given job description but did not specify how the results should be organised.

The improved prompt provided a structured table with separate columns for technical skills and business skills. It also instructed the AI to include only explicitly mentioned skills and avoid adding unsupported information.

**Conclusion:** Clear instructions and a defined output format can make skill extraction more organised and consistent.


Experiment 4: Customer Feedback Classification

### Basic Prompt

Analyze this customer feedback: "The delivery was late, but the product quality is excellent."

### Basic Prompt Output
Customer Feedback Analysis

- Sentiment: Mixed
- Positive feedback: The customer is highly satisfied with the product quality.
- Negative feedback: The delivery was delayed.
- Key insight: Product quality meets customer expectations, but delivery speed needs improvement.
- Recommendation: Improve delivery scheduling and logistics to ensure timely deliveries while maintaining product quality.

I can also classify customer feedback into Positive, Negative, and Neutral sentiments using a simple table for your analytics project.

### Improved Prompt

Act as a customer feedback analyst. Analyze this feedback and return exactly four fields: Overall Sentiment, Positive Point, Negative Point, and Suggested Action. Use concise values. Do not infer facts that are not stated. Feedback: "The delivery was late, but the product quality is excellent."

### Improved Prompt Output
- Overall Sentiment: Mixed
- Positive Point: Excellent product quality.
- Negative Point: Late delivery.
- Suggested Action: Improve delivery timeliness.

### Results
The basic prompt generated a general analysis of the customer feedback. The improved prompt specified four fields: Overall Sentiment, Positive Point, Negative Point, and Suggested Action.

The improved prompt organised the feedback more clearly by separating the positive and negative aspects and specifying the required output format.

**Conclusion:** Providing clear instructions and predefined fields helps produce more structured and consistent customer feedback analysis.

Experiment 5: Structured Table Generation

### Basic Prompt

Organize this information: Anu sold 10 units at ₹200 each. Ravi sold 15 units at ₹150 each. Meena sold 8 units at ₹250 each.

### Basic Prompt Output

| Salesperson | Units Sold | Price per Unit | Total Sales |
| ----------- | ---------- | -------------- | ----------- |
| Anu         | 10         | ₹200           | ₹2,000      |
| Ravi        | 15         | ₹150           | ₹2,250      |
| Meena       | 8          | ₹250           | ₹2,000      |
| Total       | 33         | —              | ₹6,250      |

### Improved Prompt

Act as a data assistant. Convert the following information into a Markdown table with columns: Salesperson, Units Sold, Unit Price (₹), and Total Sales (₹). Calculate Total Sales as Units Sold multiplied by Unit Price. Check the arithmetic and do not add any other data. Information: Anu sold 10 units at ₹200 each. Ravi sold 15 units at ₹150 each. Meena sold 8 units at ₹250 each.

### Improved Prompt Output 
| Salesperson | Units Sold | Unit Price (₹) | Total Sales (₹) |
| ----------- | ---------- | -------------- | --------------- |
| Anu         | 10         | 200            | 2,000           |
| Ravi        | 15         | 150            | 2,250           |
| Meena       | 8          | 250            | 2,000           |

### Results
The basic prompt generated a sales table from the given information. The improved prompt specified the exact column names and instructed the AI to calculate total sales by multiplying units sold by unit price.

The correct total sales are:
- Anu: ₹2,000
- Ravi: ₹2,250
- Meena: ₹2,000

The improved prompt provided clearer formatting instructions and highlighted the need to verify calculations.

**Conclusion:** Specific instructions about table structure and calculations help produce organised and verifiable outputs.