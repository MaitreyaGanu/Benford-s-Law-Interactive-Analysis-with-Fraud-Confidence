# Benford’s Law Interactive Analysis Tool

## Overview

This project provides an **interactive web application** for analyzing numerical datasets using Benford’s Law. Users can upload CSV files, select a column, and visually compare the actual leading digit distribution to the theoretical Benford distribution. The tool also provides a fraud confidence score based on deviation from Benford’s Law.

## Features

- **CSV Upload:** Easily upload your dataset.
- **Column Selection:** Choose which numeric column to analyze.
- **Visualization:** 
  - Bar graph for the actual leading digit frequencies.
  - Line graph for the theoretical Benford frequencies.
- **Fraud Detection Confidence:** Calculates and displays a confidence score for potential fraud based on deviation from Benford’s Law.
- **User-Friendly:** Built with [Gradio](https://gradio.app/) for a seamless interactive experience.

## What is Benford’s Law?

Benford’s Law predicts the frequency distribution of the first digits in naturally occurring datasets. According to the law, lower digits (like 1 and 2) appear as the leading digit more frequently than higher digits (like 8 and 9). Significant deviations from this distribution can indicate potential anomalies or fraud.

## How It Works

1. **Upload a CSV file** containing your data.
2. **Select the column** you wish to analyze (must be numeric).
3. **View the results:**  
   - The bar chart shows the actual frequency of each leading digit in your data.
   - The red line shows the theoretical Benford frequencies.
   - A confidence score is displayed, indicating the likelihood of fraud based on deviation from Benford’s Law.

## Example

![Benford's Law Analysis Screenshot](screenshot.png)



