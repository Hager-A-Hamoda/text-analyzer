# Text Analyzer

A desktop text analysis application built with **F#**, **.NET 10**, and
**Windows Forms**. It analyzes text and presents useful statistics,
including word, sentence, and paragraph counts.

## Features

-   Count the total number of words.
-   Count sentences and paragraphs.
-   Identify the most frequently used words.
-   Calculate the average number of words per sentence.
-   Enter text directly or load text from a `.txt` file.
-   Display analysis results and clear the input to start again.

## Example

**Input:**

``` text
Hello world! Hello again.

One short line
```

**Expected results:**

-   Words: 7
-   Sentences: 3
-   Paragraphs: 2
-   Average words per sentence: 2.33
-   Most frequent word: `hello` (2 times)

## Technologies

-   F#
-   .NET 10
-   Windows Forms
-   Visual Studio Code

## How to Run

### Prerequisites

-   Windows
-   .NET 10 SDK
-   Visual Studio Code (recommended)

### Steps

1.  Clone this repository:

    ``` bash
    git clone YOUR_REPOSITORY_URL
    ```

2.  Open the project folder in Visual Studio Code. Open the folder that
    contains `TextAnalyzer.fsproj`.

3.  Open the integrated terminal using **Terminal → New Terminal**.

4.  Make sure the terminal is in the same folder as
    `TextAnalyzer.fsproj`.

5.  Run the application:

    ``` bash
    dotnet run
    ```

6.  Enter or paste text into the application, or use **Load .txt file**
    to select a text file.

7.  Select **Analyze** to display the results. If you change the text,
    select **Analyze** again to refresh the results.

> **Important:** The repository must contain the application source
> files and `TextAnalyzer.fsproj` before these run instructions will
> work. If this repository currently contains only the README, add the
> project files before asking someone to clone and run it.

## Project Structure

The application project folder should contain the following files:

``` text
TextAnalyzer/
├── TextAnalyzer.fsproj
├── Program.fs
├── TextAnalysis.fs
├── .gitignore
└── README.md
```

Build output and temporary folders such as `bin/` and `obj/` should not
be committed.

## Project Goals

The project demonstrates how to build a simple desktop application in F#
and apply text-processing techniques to produce clear, useful
statistics.
