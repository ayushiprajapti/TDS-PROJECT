# GitHub User and Repository Data

- This project fetches user and repository data from the GitHub API for users located in Melbourne with more than 100 followers.  
- The data was gathered through API calls, specifically searching for users and fetching their detailed profiles and repositories.
- Using a Python script in VS Code, I scraped GitHub user data via the GitHub API, collecting detailed information on users in Melbourne    with over 100 followers. The data included user details and up to 500 of their most recent repositories. Google Colab was used for        analysis. 
- I discovered that hireable users with detailed bios tend to have significantly more followers.
- Developers should consider writing detailed bios and publishing repositories on weekends to attract more followers and stars

## Data Scraping Process

The data was scraped using a Python script executed in VS Code, utilizing the GitHub API to fetch detailed information about users and their public repositories. Authentication was managed with a personal access token to ensure compliance with API rate limits. The script iterated through multiple pages to gather comprehensive data on users located in Melbourne with over 100 followers. It collected essential user details, including their login IDs, names, companies, locations, email addresses, and bio information. Additionally, up to 500 of their most recently pushed repositories were retrieved, including fields such as repository names, creation dates, star counts, and license information. All fetched data was subsequently cleaned and organized for analysis. And Google Colab was used to find answers to the questions and to find the interesting facts.

## Interesting and Surprising Fact

One of the most interesting findings from my analysis was that developers who write longer bios tend to have more followers. Specifically, for every additional word in their bio, they gain an average of 7.352 more followers and hireable users with detailed bios (more than 10 words) have an average of 501.03 followers. There is a correlation of 0.188 between the number of followers and the number of public repositories. This suggests that developers with more public repositories tend to have more followers. Also, Repositories created on weekends have an average of 38.15 stars, compared to 20.10 stars for those created on weekdays.


## Actionable Recommendation

Based on my analysis, I recommend that 
1. **Write Detailed Bios**: Craft engaging and detailed bios to attract more followers. Each additional word can gain you an average of 7.352 more followers.
2. **Increase Public Repositories**: Create and maintain more public repositories to boost your visibility and follower count.
3. **Publish on Weekends**: Release repositories on weekends to get more stars and attention, as weekend projects average 38.15 stars compared to 20.10 on weekdays.

