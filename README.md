# reddit-sub-nlp
A pipeline to ingest, transform and analyse reddit submission titles in any sub over time

I started with the idea and then began looking into the feasibility of this. So far I've come to learn that:

- The official reddit API will be rather restrictive for my ambitious aims
- A historical data dump of reddit occurs and is maintained in a project called Pushshift.
- Pushshift is not open sourced and is currently experiencing some infrastructure issues, meaning the results are not as expected and/or the API isn't available. 
- In absence of the Pushshift API, a monthly data dump can be downloaded, but without filtering down first. This means that just a months worth of data will be many gigs and cover many subs... Perhaps I'll restrict my analysis timeframe, bite the bullet and do the data cleaning to get what I want? 

