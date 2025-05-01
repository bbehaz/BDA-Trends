# One Sentence to Uncover the Past & Predict the Future

## Executive Summary
The CTR Predictor Module is a comprehensive analysis and prediction system designed specifically for marketing analysts. Users can input natural language questions and instantly receive rich visualizations and future trend forecasts. This platform combines Large Language Models (LLMs) with big data tools to provide both historical analysis and predictive capabilities for marketing teams, eliminating technical barriers and enabling non-technical users to perform complex data analysis.
The system transforms natural language queries about advertising data into SQL queries, data visualizations, and predictions - all through a simple, intuitive interface that requires no technical expertise.

## Business Value
- Accelerated Decision-Making: Reduce data analysis cycles from days to minutes, enabling marketing teams to quickly adjust strategies
- Resource Optimization: Allocate marketing budgets to highest-yielding channels and timeframes through predictive insights
- Cost Reduction: Decrease reliance on specialized data analysts, reducing operational costs by 30-50%
- ROI Enhancement: Clients may experience marketing ROI improvement of 15-25%
- Competitive Advantage: Gain data-driven marketing insights to make faster, more informed decisions ahead of competitors

## Target Audience
- Marketing Managers: Decision-makers who need quick understanding of campaign performance and trends and at the same time have the domain knowledge to understand the numbers
- Advertising Specialists: Team members responsible for designing and optimizing ad strategies
- Content Creators: Creative professionals who need to understand their content performance
- C-Suite Executives: Senior management requiring high-level performance insights and forecasts

## Key Features
- Natural Language Input: Simply ask questions in plain English, no need to learn SQL or programming only some domain knowledge to ask the right questions
- Real-time Visualization: Quickly generate summary tables, charts and data visualizations
- Predictive Analytics: Go beyond historical analysis to forecast future CTR performance
- Scalable Architecture: Handle large-scale datasets, supporting various database platforms
- Self-Service Analytics: Democratize data insights for marketing teams and individuals

## Core Technologies
- **Python** (PySpark, Pandas) for data processing
- **LightGBM** for predictive modeling
- **Flask** for backend API and web interface
- **OpenAI GPT API** for natural language processing
- **Matplotlib/Seaborn** for data visualization

## Use Cases
The CTR Predictor Module addresses multiple challenges in marketing analytics:
- Marketing Performance Analysis: Understand which marketing channels, device types, or ad placements perform best
- Audience Insights: Analyze how different audience segments will respond to advertisements
- ROI Optimization: Predict future performance to optimize marketing resource allocation

## Sample Queries
The system can process various types of natural language queries, including:
- "How does CTR vary by hour of day?"
- "Compare CTR between website and mobile devices"
- "Which ad placements have the highest CTR?"
- "Show the trend of CTR over the last 30 days"
- "Predict CTR for next week by device type"
- "Compare weekend vs weekday performance across different banner positions"

## System Architecture
The platform follows a modular design:
- **NLP Agent** (GPT model) parses and translates natural language into SQL
- **Data Processing** (Spark/Pandas) retrieves and transforms data
- **Predictive Model** (LightGBM) makes forecasts
- **Visualization Engine** creates charts and tables
- **Web Interface** (Flask) delivers results to end users

## Data Requirements
The system supports multiple data sources:
- CSV format data files
- Relational databases (MySQL, PostgreSQL, etc.)
- Big data platforms (Spark, Hadoop)
- Cloud data warehouses (S3, BigQuery, Redshift)
You should modify the code to connect to your database.

## How It Works
1. Natural Language Query
Users enter simple queries like "How does CTR vary by day of the week?" or "Which device types have the highest CTR?"
2. NLP Processing
The system uses GPT models to translate natural language into:
- SQL queries for data retrieval
- Visualization instructions
- Prediction parameters
3. Data Processing & Analysis
- The system executes SQL queries against the dataset
- Feature engineering is performed for predictive modeling
- Results are formatted for visualization
4. Output Generation
- Visualizations show historical patterns
- Predictive model forecasts future performance if the query is asking for a prediction
- Results are displayed in an intuitive web interface

## Citation
If you use this tool in your research or project, please cite:
Team 13 - BDA Trends Marketplace. (2025). CTR Predictor Module. GitHub Repository. 
https://github.com/bbehaz/BDA-Trends

This project repository is created in partial fulfillment of the requirements for the Big Data Analytics course offered by the Master of Science in Business Analytics program at the Carlson School of Management, University of Minnesota.
