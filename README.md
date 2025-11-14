# Technical Assignment: Selenium Test on BrowserStack

## Task Overview

The objective of this assignment is to run a Selenium test on BrowserStack, which involves scraping articles from the **Opinion** section of the Spanish news outlet **El País**, translating article headers, and performing cross-browser testing.

### Steps

1. **Visit the Website**
   - Navigate to the website **El País**.
   - Ensure that the website's text is displayed in Spanish.

2. **Scrape Articles from the Opinion Section**
   - Navigate to the Opinion section of the website.
   - Fetch the first five articles in this section.
   - Print the title and content of each article in Spanish.
   - If available, download and save the cover image of each article to your local machine.

3. **Translate Article Headers**
   - Use a translation API of your choice (e.g., Rapid Translate Multi Traduction API).
   - Translate the title of each article to English.
   - Print the translated headers.

4. **Analyze Translated Headers**
   - Identify any words that are repeated more than twice across all headers combined.
   - Print each repeated word along with the count of its occurrences.

5. **Cross-Browser Testing**
   - Run the solution locally to verify functionality.
   - Execute the solution on BrowserStack across 5 parallel threads, testing on a combination of desktop and mobile browsers.

---

## Output Summary
"consoleoutput.txt" has the output for the following.
The script efficiently executes test cases simultaneously on multiple browser and device configurations.

