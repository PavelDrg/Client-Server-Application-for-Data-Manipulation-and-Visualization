# Client-Server-Application-for-Data-Manipulation-and-Visualization

This project introduces a versatile client-server application designed to handle data manipulation and visualization tasks efficiently. Below are the key functionalities of the application:

## Client Side:

- **User-Friendly Interface**: The client side features a simple graphical user interface  with three intuitive buttons neatly arranged at the top of the window.

- **CSV File Operations**: Seamlessly read CSV files from local storage. These CSV files, whether manually created or sourced online, are expected to contain meaningful data for analysis. In the uploaded example I have a reduced sample of the result from a machine learning model.

- **Dynamic Graph Generation**: Generate insightful graphs based on the data extracted from the CSV files. With just a click, visualize trends, correlations, and patterns within the dataset. The generated graphs are displayed elegantly within the application for easy interpretation (provided example contains confusion matrix and pie-chart graphs).

- **Effortless Document Creation**: Create rich DOCX documents effortlessly. These documents include informative titles, explanatory paragraphs about the CSV data, tabular representations of the dataset, and accompanying graphs. The documents are then seamlessly transmitted to the server for further processing.

## Server Side:

- **Efficient File Handling**: The server side efficiently handles the reception and processing of DOCX files transmitted by the client.

- **PDF Report Generation**: Automatically generate comprehensive PDF reports from the received DOCX files. These reports contain all the information from the DOCX files, excluding the tabular data from the initial CSV files.

- **Structured XML Generation**: Based on the tabular data extracted from the CSV files, the server generates structured XML files. The XML structure is tailored to represent the underlying data effectively, offering insights and facilitating further analysis.

This application employs a robust mechanism for transmitting documents or data of variable sizes, ensuring seamless communication between the client and server. With its user-friendly interface and powerful features, this client-server application completes it's objective to streamline data analysis and report tasks effectively.
