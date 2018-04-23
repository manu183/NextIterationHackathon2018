# Autonomous Semantic Search Engine

A search engine that autonomously crawls documents from a given domain including their subdomains, analyzes them and renders them into a search frontend. This implementation demonstrates the functionality with the [Stanford University](https://www.stanford.edu/)'s website. This project was implemented during the [Next Iteration Hackathon 2018](http://hackathon.nextiteration.de/)

## Web crawler

Python implementation with Scrapy [here](https://github.com/manu183/Autonomous-Semantic-Search-Engine/tree/master/pdfcrawler).

## Document analysis

Python implementation using [Watson Natural Language Understanding](https://www.ibm.com/watson/services/natural-language-understanding/) and a custom random forest [here](https://github.com/manu183/Autonomous-Semantic-Search-Engine/blob/master/backend/process.py).

## Web frontend

A react frontend that displays the information with additional image information using [Bing Image Search](https://azure.microsoft.com/en-au/services/cognitive-services/bing-image-search-api/) [here](https://github.com/manu183/Autonomous-Semantic-Search-Engine/tree/master/search-frontend).

## brew Dependencies
- Swig etc. for Textract: https://textract.readthedocs.io/en/stable/installation.html
- Ghostscript: https://wiki.scribus.net/canvas/Installation_and_Configuration_of_Ghostscript
- ImageMagick 6: https://github.com/ImageMagick/ImageMagick/issues/953
