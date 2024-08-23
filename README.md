# web_scrap
Application that will scrap research papers and spit out bullet point summaries. 

What I want this project to do and how:

I want it to be given an input SEED url. Example seed: https://pubmed.ncbi.nlm.nih.gov/?term=Scoliosis 
This link redirects to the National Library of Medicine(NIH) search page with the term Scoliosis. 

Maybe in the future the application can be given any term it wants in an input field and search using that term.

This link will be the initial SEED url.
From this URL, the crawler should visit the top X free articles and input those articles into an AI with instructions to summarize them into bullet points.






Things to do:
On the search page, make sure to filter by free full text.
The search results have hrefs # which are what we are looking for.
https://pubmed.ncbi.nlm.nih.gov/31894928/ Is example link


Check for robots.txt

I noticed the links on NIH just have abstracts and then free links to other pages.
So crawler could start out just using abstracts and staying on NIH pages 
Future updates maybe scrap these external links as well.
