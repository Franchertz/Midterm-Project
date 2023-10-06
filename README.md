# MIDTERM-PROJECT 

  ### CLIMATE CHANGE'S IMPACT ON APPAREL MANUFATURING IN CALGARY CANADA

Team members:

    Quoc Thach Nguyen (RED)
    Franklin Anozie

## PROJECT/GOALS

    1. Our midterm project has the primary goal of forecasting upcoming weather patterns,
    with a specific focus on temperature trends in Calgary, Canada. This initiative is aimed
    at providing valuable insights to the ABC Apparel Company to optimize its strategy for
    producing jackets. In this consultancy role for ABC, it is imperative to ascertain whether
    the temperature is expected to increase or decrease in the forthcoming years.

    2. Our specialization lies in crafting season-specific apparel, which encompasses the
    production of winter jackets, lightweight fall jackets, and spring sweaters.
    The ultimate objective is to harmonize our production processes with the expected
    weather conditions, allowing us to cater to the unique climate needs of the city more effectively.

## PROCESS

### STEP 1: EXPLORE LOGISTICS AND INDIVIDUAL INTERESTS

    1. Schedule Coordination: Organize team members' calendars to allocate
    dedicated collaborative work time.
  
    2. Interest Discovery: Delve into each team member's areas of interest and
    expertise to harness their strengths effectively.
  
    3. Project Ideation: Initiate brainstorming sessions to develop strategies
    for tackling weather prediction and its implications on jacket production.

### STEP 2: REFINE PROBLEM STATEMENT AND DATA COLLECTION

    1. Problem Statement: Conclude the definition of our objective, centered on
    forecasting weather patterns in Calgary and its influence on Apparel production.

    2. Data Sources: Determine and verify the datasets essential for precise weather
    predictions. We agreed on Kaggle.

    3. Gather historical weather data for the cities you are interested in.
    It appears you have a dataset with historical weather data that includes
    temperature and precipitation measurements.
    Dataset: `Canadian_climate_history.csv`
    Dataset type: `Timeseries`, dated from 1940 - 2019, having 29,221 rows and 36 columns


    4. Repository Establishment: Establish a GitHub repository for the purpose
    of organizing, maintaining, and distributing code and data.

### STEP 3: DATA PREPROCESSING

    1. Clean the data by handling missing values and outliers.

    2. Create a target variable that represents whether the temperature
    will "rise" or "fall" based on your criteria (e.g., comparing today's temperature with tomorrow's).

    3. Prepare the data by selecting relevant features (e.g., MEAN_TEMPERATURE and TOTAL_PRECIPITATION)
and the target variable.

### STEP 4: EXPLORATORY DATA ANALYSIS (EDA)

    1. Explore the data to gain insights into the relationships between temperature,
    precipitation, and other factors.

    2. Visualize data patterns and correlations.

    3. Prepare for data modelling.

### STEP 5: MODEL SELECTION

    1. Choose an appropriate model to predict whether the temperature will rise or fall.

    2. Some suitable models include logistic regression, RMSE (Root Mean Square Error)
    and MAE (Mean Absolute Error).

### STEP 6: DASHBOARD CREATION AND INITIAL PRESENTATION DRAFT

    1. Data Visualization: Use Python libraries, Tableau to tell a story on the impact of
    climate change on apparel manufacturing.

    2. Dashboard Development: Initiated the development of a dashboard to present the insights
    interactively.

## RESULTS

Exploratory Data Analysis (EDA) Insights:

    During our exploration of the data, we identified numerous instances of zero values in both
    temperature and precipitation columns. After careful examination and analysis, we made the
    decision to retain these values as they are valid. In colder climates like Calgary, it is
    plausible to have zero temperatures and precipitation.

Model Performance:

    1. Initially, we employed a linear regression model to assess the relationship between the
    dependent variable (temperature) and the independent variable (precipitation). However, the
    resulting R-squared value was relatively low, ranging from 13% to 21%, indicating a weak
    explanatory power of the model.

    2. In pursuit of improvement, we conducted experiments involving various data transformation
    and scaling techniques, including Log Transformations, StandardScaler, and Min-Max scaling.
    Despite these efforts, there was no substantial enhancement in the R-squared value.

    3. In response to the limited success with linear regression, we transitioned to a more advanced
    modeling approach, specifically ARIMA (AutoRegressive Integrated Moving Average). ARIMA is
    well-regarded for its effectiveness in handling time series data and presented a more promising
    avenue for forecasting future weather patterns.

Projected Weather Trends:

    1. The forthcoming winter is expected to experience a temperature increase, with a shift from
    -8.4°C in 2019 to -7.4°C in 2020.

    2. Spring temperatures are projected to undergo a slight decline, moving from 5.7°C in 2019
    to 5.5°C in 2020.

    3. Fall temperatures are predicted to rise, transitioning from 5.1°C in 2019 to 5.7°C in 2020.
    
## CHALLENGES 

    1. We initially confronted the challenge of a low R-squared value in our initial modeling attempts,
    prompting the need to delve into advanced modeling techniques.

    2. Time constraints emerged as a substantial challenge, impacting the depth of our analysis
    and modeling efforts.

    3. Resource limitations were also a hurdle we encountered during the project, influencing
    the scope of data collection and analysis.

	
## FUTURE GOALS

    1. Our future objectives involve refining the ARIMA model to achieve more accurate predictive
    insights and further enhance its performance.

    2. We aim to broaden our analysis by exploring additional variables and data sources. This
    includes investigating factors such as wind speed, humidity, and, notably, pollution indices.
    These additional variables can provide a more nuanced and comprehensive foundation for our
    predictive models, contributing to a deeper understanding of weather patterns.

	