# culls

1.Data Source
    - api (if we want to model the "evolutionary process" of something that is being tracked on the internet, we can use an api)
    - csv, excel, json ( perhaps we can read in gene data as a spreadsheet file, pandas to read data)
2. Data Ingestion
    -  we can use apache airflow (the way that I understand it, this is a tool that allows you to ingest data and to place it in a data warehouse ==> I am not sure why I couldn't just use pandas as a way to read data, but considering that this using tools like this seems to be something that data engineers do, if I use it for my project I think I'll learn along the way why it is used/why it is useful)