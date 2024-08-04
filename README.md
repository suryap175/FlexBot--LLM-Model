# FlexBot- Advanced Chatbot-Your-Health-Fitness-Productivity-Guru
## Overview
This chatbot represents a significant advancement in prompt engineering by facilitating queries and analysis. It utilizes Langchain's language model to generate intelligent and contextually relevant prompts, enabling users to efficiently interact with data across three categories: Health, Productivity, and Fitness. The chatbot aims to enhance decision-making and streamline data exploration by leveraging Langchain's cutting-edge language models and presenting information through an intuitive Streamlit user interface. It provides recommendations and answers queries about apps, addressing user needs and suggesting relevant applications based on input. The goal is to target health enthusiasts and productivity seekers, empowering users from diverse backgrounds to gain insights and achieve their health and fitness goals.


## Data Source
#### Web Scraping
App information for each category is scraped using the app function from the Google Play Scraper library. This data includes app details such as title, score, ratings, ads presence, price, whether it's free, real installs, release date, in-app product price, and the app icon. Dataframes are created for each category with selected columns, enabling comprehensive analysis and insights into app performance and user feedback.

## Data Collection
#### Amazon S3

Data is stored in Amazon S3, utilizing the boto3 library for authentication through AWS access key ID and secret access key. This setup is ideal for archiving, data backup, and facilitating collaborative data analysis workflows.

## Model Development

**1. Framework - Langchain:**
 Langchain serves as the main framework, providing structure and tools to integrate various components such as language models, data processing agents, and user interfaces. It streamlines the development workflow, making it easier to handle natural language processing tasks.

**2. Chat Model Used - ChatOpenAI:**
 ChatOpenAI is responsible for generating responses to user inputs. Using advanced natural language processing, it interprets queries and produces relevant and coherent responses, offering a more engaging and interactive experience.

**3. Agent Used for Data Processing - pandas_dataframe_agent:**
 This agent manages the underlying data using the pandas library, handling tasks like data cleaning, transformation, and organization. It ensures that the data is in a format the language model can effectively utilize.

**4. LLM Model Used - GPT4:**
The Generative Pre-trained Transformer model, GPT-4, serves as the core engine for language understanding and generation. It excels in comprehending context and generating human-like text, forming the backbone of the chatbot's ability to understand user intent and respond appropriately.

In summary, the Langchain framework integrates the components, with ChatOpenAI managing interactions, pandas_dataframe_agent handling data, and GPT-4 providing language capabilities. Together, these elements create an advanced and efficient chatbot capable of processing and responding to user inputs naturally and contextually.

## Streamlit Instructions:

1. Select the category of apps from the three drop-down menus (Fitness, Health, and Productivity).
2. Enter your query
3. Enter if any app summarizations needed
4. Look for the visualizations

   
Codelab Link: https://codelabs-preview.appspot.com/?file_id=11wP6_UTPNx8adUSvqu2HfzSj3Jyls0qRqGa70TaNgDM#0
