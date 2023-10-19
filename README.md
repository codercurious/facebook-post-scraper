# Facebook post scraper
Interested in using this scraper? Get it here: [Facebook post scraper](https://apify.com/curious_coder/facebook-post-scraper?fpr=ve081&fp_sid=github_facebook-post-scraper)
The Facebook posts scraper is an Apify actor designed to extract facebook posts from a persop, page, group, etc. With this actor, you can effortlessly gather valuable data from Facebook posts for various purposes, such as market research, lead generation, and competitor analysis.

**Main Features:**

1. **Efficient post Data Extraction:** The actor enables you to extract detailed information about posts, including their content, entities in content, date, author details, engagement insights and other relevant data available.

2. **Customizable Data Output:** You have the flexibility to choose which post details you want to extract. The actor allows you to define the output fields according to your specific requirements, ensuring that you obtain the most relevant information.

3. **Easy-to-Use Configuration:** The actor provides a simple and intuitive configuration interface. You can specify the Facebook URL you wish to scrape, set pagination limits, and define the output fields all within the user-friendly configuration settings.

4. **Proxy Support:** To enhance reliability and avoid rate limiting issues, the actor supports proxy usage. You can provide a list of proxies that will be rotated automatically to ensure smooth and uninterrupted scraping.

5. **Scalability and Performance:** The actor is built on the Apify platform, which ensures scalability and excellent performance. It utilizes parallel processing to scrape multiple pages simultaneously, maximizing efficiency and minimizing the overall scraping time.

6. **Data Export and Integration:** Once the scraping process is complete, you can easily export the extracted data in various formats such as JSON, CSV, or Excel. This allows for seamless integration with other tools and platforms for further analysis and utilization.

7. **Automatic Retry and Error Handling:** In case of temporary issues like network failures or timeouts, the actor has built-in automatic retry functionality. It intelligently handles errors to ensure a smooth and uninterrupted scraping experience.

## Getting started

1. Install [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg) chrome extension 
2. Login to your facebook account
3. While you are on facebook tab, Click on the extension and export the cookies 
4. Paste the cookies to this actor's `Cookie` input field
5. Specify the Facebook profile or group URL you want to scrape posts from.
6. Set pagination limits to determine the number of pages to scrape.
7. (Optional) Configure proxy settings for enhanced reliability.
8. Run the actor and obtain the extracted data in your preferred format.

The Facebook posts Scraper actor is an invaluable tool for businesses, researchers, and marketers seeking to gain insights from Facebook posts. By automating the data extraction process, it simplifies the task of collecting post information and empowers you to make data-driven decisions based on the extracted data.


## Sample data

![scraped 4k+ facebook group posts](https://ik.imagekit.io/webscraper/facebook-group-posts-scrape.png?updatedAt=1696184556095)

Here is the sample json output of this actor:

```json
{
	"createdAt": 1692000008,
	"url": "https://www.facebook.com/groups/duxsoup/permalink/1254207048553531/",
	"user": {
		"id": "100057436000660",
		"name": "Dux-Soup",
		"url": "https://www.facebook.com/DuxQuack"
	},
	"text": "Let's welcome our new members:\nUna Doyle,\nMar Benavent Mas,\nPatxi Gadanon,\nSiva Inc.,\nFabio Keidel Zanzeri,\nAdam Lamprey,\nVakeesan Mahalingam,\nDeirdre OConnor",
	"reactionCount": 2,
	"shareCount": 0,
	"commentCount": 0,
	"cursor": "AQHRufSqSbfd7f3YHTvdAfdCYAL9MO11csBuRKzs6f4r6__veuAPI5DFSiR8Vc_Pzb2Yr0W-Mx3seG7Njs5mgRoWGQ:eyIwIjoxNjkyNTk1MDczLCIxIjozNTg2LCIyIjoxNjkyNTk1MDY1LCIzIjoxLCI0IjoxLCI1Ijo0fQ=="
}
```
