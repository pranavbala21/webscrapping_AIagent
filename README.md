# Web Scraping and Summarization Tool

This tool is an AI-powered script that accepts a URL, extracts the web page's content, and generates a concise summary of approximately 100–150 words. It uses open-source libraries for web scraping, content extraction, and summarization.

---

## Features

- Web Scraping: Extracts content such as headings and paragraphs from a provided URL.
- Content Summarization: Generates a concise summary using the Hugging Face `facebook/bart-large-cnn` model.
- Error Handling: Includes mechanisms to handle invalid URLs, empty content, and other runtime errors.
- Content Length Control: Ensures the summary is within the desired word range (100–150 words).

---

## Requirements

### Python Libraries

- `beautifulsoup4`: For parsing HTML content.
- `requests`: For fetching web pages.
- `transformers`: For summarization using pre-trained models.

Install the required libraries using pip:

```bash
pip install beautifulsoup4 requests transformers
```

---

## Usage

1. Clone the repository or download the script.
2. Run the script using Python:

```bash
python script_name.py
```

3. Enter the URL when prompted. For example:

```plaintext
Enter the URL: https://example.com
```

4. The script will:

   - Fetch the content of the URL.
   - Extract headings and main content.
   - Generate a summary of the content.

5. The output will display:

   - Title of the webpage.
   - Extracted headings.
   - Summary of the content.

---

## Example Output

**Input**:

```
https://example.com
```

**Output**:

```plaintext
Title: Example Website

Headings:
- Welcome to Example
- About Us
- Our Services

Summary:
This website provides information about Example, including its services and mission. It highlights key aspects of their offerings, aiming to cater to user needs effectively. Example emphasizes innovation and customer satisfaction as core values.
```



