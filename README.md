# News Article Scraper

This project is a web scraper built with Python that extracts articles from news websites and converts them into a simple structured format:

- **Title**: Converted to Title Case  
- **Date**: Extracted from the article metadata  
- **Source**: Embedded hyperlink to the original article  
- **Content**: Full article body, cleaned and structured

## Example Output

**Title**: Ukraine Conflict Sees Escalation in East  
**Date**: August 8, 2025  
**Source**: [BBC News](https://www.bbc.com/news/ukraine-conflict)  
**Article**:  
_The article goes here..._

## Setup

```bash
pip install requests beautifulsoup4
