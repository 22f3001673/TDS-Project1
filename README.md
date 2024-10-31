# TDS-Project1-GitHub API
IITM TDS Project 1 (GitHub API)

# Mumbai GitHub Users and Repositories Data
- This dataset was scraped using the GitHub API to collect data on users in Mumbai with over 50 followers and their repositories. The data anaysis was done on cloud-based Google Colab Python code with Pandas library for data analysis and manipulation.
- Analysis revealed that a significant portion of Mumbai-based developers focus on web technologies, with JavaScript and Python as the most common languages. Hireable developers prefer to make themselves more accessible by sharing their email addresses.
- Developers should prioritize building skills in JavaScript and Python to align with the demand in the Mumbai tech community. They should keep their bios concise which tends to attract more followers. Providing an email address is good for better hireability.


## Data Scraping Process
Using Python and the GitHub API, it has collected user profiles for individuals located in Mumbai with over 50 followers. For each user, it retrieved additional information on their public repositories (up to 500 per user), including metadata such as stars, languages, and creation dates. Data cleaning was applied to standardize company names, and the dataset was saved as two CSV files: `users.csv` and `repositories.csv`.

## Files in This Repository
- `users.csv`: Contains detailed profile information for each user, including their GitHub login, name, company, location, email, and GitHub stats (followers, following, public repositories, and account creation date).
- `repositories.csv`: Includes metadata for each repository, such as the repository's full name, creation date, star count, language, and license type.
## Key Insights and Recommendation
This analysis of Mumbai developers shows a high prevalence of web development projects, suggesting a demand for skills in web-related languages. Therefore, developers interested in gaining traction within the Mumbai tech community might benefit from focusing on JavaScript, Python, and HTML. Also, Java is more popular as compared to C/C++. Regarding their GitHub profiles, a negative correlation suggests that longer bios might actually correlate with fewer followers, possibly indicating that users with shorter, more concise bios tend to attract more followers. This finding could mean that followers prefer simpler or more direct descriptions. The hireable users are indeed more likely to provide contact information, which is intuitive since these developers may want to make it easy for potential employers or collaborators to reach them.
