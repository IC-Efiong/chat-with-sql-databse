
# MySQL Python Chatbot with Mistral AI

This project guides you through the development of a chatbot that can interpret natural language queries, generate SQL queries, and fetch results from a SQL database, all in an intuitive and user-friendly way. It utilizes the power of Mistral AI, integrated with a Streamlit GUI for an enhanced interaction experience.

## Features
- **Natural Language Processing:** Leverage Mistral AI's capabilities to understand and respond to user inquiries in a conversational manner.
- **SQL Query Generation:** Dynamically create SQL queries tailored to user requests, ensuring accurate and efficient data retrieval.
- **Database Interaction:** Seamlessly connect to SQL databases to fetch relevant data, providing a practical demonstration of database interactions.
- **Streamlit GUI:** Enjoy a user-friendly interface built with Streamlit, making the chatbot accessible to users of all backgrounds.
- **Python-based:** Benefit from a Python-driven development showcasing modern coding practices and best practices in software engineering.


## Brief Explanation of How the Chatbot Works
The chatbot streamlines data retrieval by translating your natural language queries into SQL commands using Mistral AI. These queries are then executed against a SQL database, and the results are presented in a clear and understandable format. This efficient process involves seamless integration with Mistral AI and a SQL database, all within a user-friendly Streamlit application.

Consider the following diagram to understand how the different chains and components are built:
![Alt text]("image/chatbot-diagram.png")

## Installation

Ensure python is installed on your system. Then clone the repository 

```bash
git clone [repository-link]
cd [repository-directory]
```
install the required packages
```bash
pip install -r requirements.txt
```

Create your own .env file with the necessary variables, including your API key:
```bash
OPENAI_API_KEY=[your-openai-api-key]
```

## Usage

To launch the streamlit app and interact with the chatbot
```streamlit
streamlit run app.py
```


## License

This project is licensed under the Apache 2.0 License - see the LICENSE file for details.

