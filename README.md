# web_crawl_til_you_bawl

## An adventure in Bigger Data

![May the fourth](https://media.giphy.com/media/26FmQ6EOvLxp6cWyY/giphy.gif)

### **The Data**

The data we used comes from Common Crawl, an open source project that runs a web crawler and posts the website html data, metadata, and extracted text on a public S3 bucket. We decided to take a look at the extracted text from a subset of the data in order to understand which words were appearing on websites with the highest frequency.

### **The Goal**

The goal of our project was to gain experience using "Big" data. Our aim was to develop a model from the text data using LDA.

### **Our Process**  
We fumbled, and fumbled, and fumbled, and fumbled.... Damien ran a loader that switched his computer to Python 2. I ran around getting updates from other teams to gain insights from their respective approaches.

The main challenge was in properly downloading the data in a useful format. We were able to only get the individual words and their tf-idf counts, but these words were independent from each other, making any analysis impossible without the corresponding document.

Thanks to Steven, we were able to download the documents into a CSV at around 3:45. Then Erin said, "This is getting very verbose."  It was at that point we decided to stop writing the readme.

![Better luck next time](https://media.giphy.com/media/3o7buguVhhMMXZtDR6/giphy.gif)
