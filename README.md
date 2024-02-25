# Detect and Extract Table from PDF file

### Concept
Input: pdf -(pdf2image)> image by page -> check table within image or not (langchain + Gemini-pro-vision) -> extract table as html (langchain + Gemini-pro-vision)


- We need to install poppler for pdf2image
```cmd
sudo apt-get install poppler-utils
```