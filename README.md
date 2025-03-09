# CSC311_WeatherApplication
A modern Java application for analyzing weather data from CSV files, demonstrating the use of modern Java features introduced in Java 15-23.The application demonstrates a completely class-free design, relying instead on:

Records for data representation
Interfaces with default and static methods
Functional programming with lambdas and streams


Features Implemented:

Parse and analyze weather data from CSV files
Calculate average temperatures for specific months
Identify days with temperatures above thresholds
Count rainy days
Categorize temperatures using enhanced switch statements
Generate weather summaries

Modern Java Features Implemented:

Java Records to represent weather data
Enhanced switch (introduced in Java 14 and finalized in later versions)
Text Blocks for generating output (introduced in Java 15).
Pattern Matching for switch or any other feature from Java 15–23 (e.g., String.stripIndent, virtual threads if relevant).

Project Structure


weatheranalyzer package:
WeatherDataAnalyzer.java: main interface and implementation
WeatherApp.java: application

resources:
weatherdata.csv - Sample weather data

Java 21 or higher recommended (for virtual threads)
Java 16+ required (for pattern matching and records)
