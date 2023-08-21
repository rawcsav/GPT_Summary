# PDF Summarization

This script summarizes a collection of PDF research papers using OpenAI's GPT-4 language model.

## Prerequisites

- You need to have an OpenAI API key to use this script.
- Install the necessary libraries using the following command:

```
pip install openai pypdf3 nltk tqdm tiktoken
```

## How to use

1. Set an environment variable called `OPENAI_API_KEY` with your OpenAI API key.

```
export OPENAI_API_KEY=<your_api_key>
```

2. Run the script using the following command format.

```
python pdf_summarization.py
```

3. Enter the path to the folder containing the PDFs you want to summarize when prompted.

### Example

1. Run the script:

```
python pdf_summarization.py
```

2. Enter the path to the folder containing the research papers:

```
Enter the path to the folder containing the PDFs to summarize: /path/to/pdf/folder/
```

## Output

The script will output a complete summary for each research paper in the folder. It will print the summaries to the console.

## Note

If you reach the rate limits for the OpenAI API, the script will add a 1.5-second delay between requests to avoid overloading the rate limits. It will display a progress bar indicating the progress of summarizing the research papers using the GPT-4 language model.