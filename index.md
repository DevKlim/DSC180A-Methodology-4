# DSC 180A Methodology Assignment 4

**Name:** Kliment Ho
**Email:** klh005@ucsd.edu

**Section:** B26
**Mentor:** Ali Arsanjani

---

### Project Brainstorming

**What is the most interesting topic covered in your domain this quarter?**
The most interesting topic has been the alignment and control of Large Language Models (LLMs). This includes techniques like adjusting model behavior with temperature settings, ensuring factual accuracy through grounding, and expanding model capabilities with agentic function calling.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
For the Quarter 2 Project, I plan to build upon the work from the first quarter by taking a more holistic approach to analyzing factuality in social media posts. This would involve developing a multi-faceted system that not only checks claims but also assesses the context, potential biases, and manipulation techniques present in the content.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
A key change would be to utilize agents to gather real-time information. This would allow the system to make more accurate and grounded choices when evaluating the factuality of a claim, as it could reference the most current events and data available on the web.

**What other techniques would you be interested in using in your project?**
I am interested in learning how to organize a cost-effective cloud architecture for automating data preprocessing and scraping. For preprocessing large files, a system using a service like **AWS S3** or **Google Cloud Storage** to trigger serverless functions (**AWS Lambda** or **Google Cloud Functions**) could efficiently handle data ingestion. For scraping difficult websites like Twitter or Reddit, using tools like **Playwright** or **Selenium** for browser automation, combined with proxy services to manage rate limits, would be effective. These tasks could be containerized with **Docker** and run on-demand using services like **AWS Fargate** or **Google Cloud Run** to keep costs low.