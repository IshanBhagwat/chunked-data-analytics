# Chunked Data Analytics

A pure-Python tool that processes large datasets in memory-efficient chunks, 
parsing each chunk into dictionaries to analyze top posts, followers, 
following, and unique content categories.

## Overview

Instead of loading an entire dataset into memory at once, this project 
splits the data into smaller chunks, parses each chunk into structured 
dictionaries, and runs the same analysis loops across all chunks to 
extract key insights from the full dataset.

## Features

- **Chunked Data Processing**: Splits large datasets into manageable chunks, 
  avoiding the need to load everything into memory at once.
- **Dictionary-Based Parsing**: Converts each chunk into structured 
  dictionaries for fast, consistent analysis.
- **Highest Posts**: Identifies the record with the highest number of posts.
- **Highest Followers**: Identifies the record with the highest follower count.
- **Highest Following**: Identifies the record with the highest following count.
- **Unique Categories**: Builds the complete set of all distinct categories 
  present across the dataset.

## Tech Stack

Python (built using only core/built-in modules — no external libraries)

## How to Run

```bash
git clone https://github.com/IshanBhagwat/chunked-data-analytics.git
cd chunked-data-analytics
python data_processing.py
```

*(Replace `data_processing.py` with your actual script filename if different.)*

## What I Learned

- Processing large datasets efficiently using chunking instead of loading 
  everything into memory at once
- Parsing raw data into structured dictionaries for repeated, consistent analysis
- Writing analysis loops to extract maximum values and unique sets across 
  multiple data chunks
- Thinking about memory efficiency and scalability when working with 
  large datasets in pure Python
