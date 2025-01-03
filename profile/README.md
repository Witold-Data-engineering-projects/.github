# Witold's Data Engineering Portfolio

🙋‍♀️Welcome to my Data Engineering portfolio! This organization contains example projects showcasing my skills in data engineering, from API integrations and data pipelines to data storage solutions and visualization.

## About Me

I'm a data engineer who focuses on building secure, efficient, and scalable data solutions. My background includes experience with APIs, SQL, PySpark, Azure Databricks, Azure Datafactory, Synapse, and other data engineering tools and technologies.

## Featured Projects

Here are some of the projects you’ll find in this organization:

### [Project 1: Emplifi API Data Pipeline](https://github.com/Witold-Data-engineering-projects/Emplify-API-Data-Pipeline)

**Overview**: A project demonstrating API data extraction and transformation using Python, designed to pull social media metrics from the Emplifi API.
* API Integration: Uses the Emplifi API to pull social media metrics.
* Dynamic Configuration: Credentials, SSL certificates, and other configurations are fetched from a .env file for local development and are planned to be migrated to Azure Key Vault for deployment.
* Custom Transformation Logic: Converts nested JSON API responses into clean DataFrames using pandas.
* Multi-Level Data Insights: Supports metrics aggregation at both profile and post levels.
* Secure Practices: Employs SSL certificates and environment variables for safe API access.

### [Project 2: Properties Data Scraper](https://github.com/Witold-Data-engineering-projects/Properties)


**Overview**: This project scrapes property listings from the Rightmove website for several UK towns and stores the results in a MySQL database. The data collected includes property details such as title, address, price, and more. The project uses Python for web scraping and data processing, and SQLAlchemy to manage database connections.
* Python for scripting
* BeautifulSoup for web scraping
* SQLAlchemy for handling database connections and queries
* Pandas for data manipulation
* MySQL as the database

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
