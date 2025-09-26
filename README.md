# RSVP Movies Case Study  

This project analyzes three years of movie data for RSVP Movies, a leading production company in India. The goal was to extract insights and provide recommendations that could help RSVP plan its next projects with a global audience in mind.  

## Problem Statement  
RSVP Movies wanted to explore global movie trends across genres, ratings, production houses, and audience engagement. By leveraging SQL-based analysis, the aim was to identify what kinds of films have higher success potential, when to release them, and which actors or production houses to collaborate with.  

## Dataset Overview  
- Tables included: movies, genre, ratings, names, director_mapping, role_mapping  
- Key columns analyzed: release year, duration, genres, ratings, languages, production companies, actors, directors  

## Analysis & Insights  
- March had the highest movie releases; 2017 was the most productive year  
- Drama emerged as the most dominant genre, followed by comedy and thriller  
- Movies with median rating of 7 were the most common, showing audience preference for well-balanced entertainment  
- Marvel Studios received the highest votes worldwide, showing global influence  
- Vijay Sethupathi was identified as the top Indian actor by weighted ratings  
- German and Italian films drew strong engagement, showing language diversity impact  

## Recommendations  
- Focus on drama and thriller genres for global appeal  
- Align releases with March trends for maximum reach  
- Collaborate with popular production houses (e.g., Marvel Studios) for visibility and quality  
- Include diverse languages like German and Italian to expand global reach  
- Aim for runtimes between 100–110 minutes, which perform best across successful genres  

## SQL Queries Explored  
- Movie counts by year and month  
- Null value checks and data cleaning  
- Genre-wise distribution of movies and durations  
- Top actors, actresses, and directors ranked by ratings and votes  
- Highest grossing movies across genres and years  
- Production houses ranked by votes and number of hits  
- Advanced insights: running totals, moving averages, multilingual film analysis  

## Key Learnings  
- SQL is a powerful tool for turning raw tabular data into actionable business insights  
- Audience preferences can be quantified through median ratings, vote counts, and genre popularity  
- Strategic planning (genre, release timing, collaborations) directly ties into profitability  

## Tech Stack  
- SQL (queries for aggregation, joins, window functions)  
- Excel/PPT/PDF for reporting and visualization  
- Documentation of queries and insights for reproducibility  

## Applications  
- Helps RSVP Movies identify the right genres, actors, and production houses for their next project  
- Provides data-driven guidance on release timings and runtimes  
- Offers a scalable framework for applying SQL analytics to other entertainment datasets  
