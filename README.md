# Analyze-Generate-Taylor-Swift-Lyrics
This analysis explores the lyrics of Taylor Swift's albums (up to 2022) to uncover trends, patterns, and sentiments. By utilizing Natural Language Processing (NLP) techniques, sentiment analysis, and data visualization, we gain insights into the evolving themes and moods of her music, including whether she subtly hinted at her album Midnights before its release. The analysis also employs a Markov Chain model to generate new lyrics based on patterns found in Taylor Swift’s existing songs from albums up to 2022.


### Requirements:
- Python 3.12.4
- Jupyter Notebook 7.1
- Libraries: pandas, nltk, matplotlib, re, requests, collections

### Features
Data Collection:
- Lyrical Data Scraping: Collects Taylor Swift’s lyrics data from her entire catalog of albums through publicly accessible datasets, focusing on her works up to 2022.
- Album Metadata: Each song's album name and release year are mapped, ensuring a comprehensive understanding of her lyrical evolution up to 2022.

Data Analysis:
- Time-Based Keyword Mentions: Analyzes mentions of time-related keywords (e.g., "night," "day," "midnight") in Taylor Swift's lyrics to uncover trends in her thematic content across albums up to 2022.
- Sentiment Analysis: Applies the SentimentIntensityAnalyzer to evaluate the emotional tone of her lyrics over time, providing a compound sentiment score for each song from the albums released by 2022.
- Word Frequency: Computes the most commonly used words in Taylor Swift's lyrics, identifying recurring themes and topics across all her albums up to 2022.

Visualizations:
- Trends in Time-Based References: Generates visualizations to illustrate how mentions of "night," "day," and "time" have evolved over the years, covering albums up to 2022.
- Album Sentiment Comparison: Visualizes the overall sentiment (positive, negative, neutral) across Taylor Swift’s albums released by 2022, helping track emotional shifts in her music.
- Comparison of Day vs. Night Mentions: Visualizes the comparison between references to "day" and "night" over the years to highlight any shifts in thematic focus.

New Lyric Generation:
- Uses a Markov Chain model to generate new lyrics based on patterns found in Taylor Swift’s existing songs from albums up to 2022. The generated lyrics are then analyzed for sentiment to classify them as positive, negative, or neutral.

### Insights:
- Evolving Themes: The analysis reveals how Taylor Swift’s thematic focus, particularly on concepts like "time," "night," and "day," has evolved through her albums, from 2006 to 2022.
- Emotional Tone: The sentiment analysis offers insights into how her music’s emotional tone has shifted from album to album, highlighting periods of high positivity or introspective melancholy.
- Trend Spotting: By visualizing the frequency of key words and the sentiment of her songs, this project provides a unique view of Taylor Swift's songwriting process and the emotional landscape of her music over time.

By using data science techniques, this project aims to provide a deeper understanding of Taylor Swift's songwriting patterns, emotional content, and the evolving themes that define her career. Whether you're a fan, music enthusiast, or data analyst, this analysis offers valuable insights into the storytelling behind one of pop music’s biggest icons, based on her albums up to 2022.

### Project Screenshot
![Alt text](https://github.com/brianwpiano/Analyze-Generate-Taylor-Swift-Lyrics/blob/main/Screenshot%202024-11-28%20212227.png)
![Alt text](https://github.com/brianwpiano/Analyze-Generate-Taylor-Swift-Lyrics/blob/main/Screenshot%202024-11-28%20223218.png)
![Alt text](https://github.com/brianwpiano/Analyze-Generate-Taylor-Swift-Lyrics/blob/main/Screenshot%202024-11-28%20223231.png)
![Alt text](https://github.com/brianwpiano/Analyze-Generate-Taylor-Swift-Lyrics/blob/main/Screenshot%202024-11-28%20223245.png)
![Alt text](https://github.com/brianwpiano/Analyze-Generate-Taylor-Swift-Lyrics/blob/main/Screenshot%202024-11-28%20223256.png)
![Alt text](https://github.com/brianwpiano/Analyze-Generate-Taylor-Swift-Lyrics/blob/main/Screenshot%202024-11-28%20223311.png)
![Alt text](https://github.com/brianwpiano/Analyze-Generate-Taylor-Swift-Lyrics/blob/main/Screenshot%202024-11-28%20223326.png)
![Alt text](https://github.com/brianwpiano/Analyze-Generate-Taylor-Swift-Lyrics/blob/main/Screenshot%202024-11-28%20223336.png)

## Run the app

Clone this repo then `cd Analyze-Generate-taylor-Swift-Lyrics`.

Assuming you have Python3 installed on a Windows 10 or 11 or on MacOS, run this commands:

``` bash
Analyze-Generate-taylor-Swift-Lyrics.ipynb
```

---
