### Purpose

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

### Project Description

In this project:
- the fact and dimension tables for a star schema for a particular analytic focus is defined;  
- an ETL pipeline that transfers data from files in two local directories into these tables in Postgres using Python and SQL are written.