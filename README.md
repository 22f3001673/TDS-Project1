# TDS-Project1-GitHub API
IITM TDS Project 1 (GitHub API)

# Mumbai GitHub Users and Repositories Data
- This dataset was scraped using the GitHub API to collect data on users in Mumbai with over 50 followers and their repositories.
- Analysis revealed that a significant portion of Mumbai-based developers focus on web technologies, with JavaScript and Python as the most common languages.
- Developers should prioritize building skills in JavaScript and Python to align with the demand in the Mumbai tech community. They should keep their bios concise which tends to attract more followers. The "hireable" status is a fairly reliable indicator that the user is open to contact.


## Data Scraping Process
Using Python and the GitHub API, it has collected user profiles for individuals located in Mumbai with over 50 followers. For each user, it retrieved additional information on their public repositories (up to 500 per user), including metadata such as stars, languages, and creation dates. Data cleaning was applied to standardize company names, and the dataset was saved as two CSV files: `users.csv` and `repositories.csv`.

## Files in This Repository
- `users.csv`: Contains detailed profile information for each user, including their GitHub login, name, company, location, email, and GitHub stats (followers, following, public repositories, and account creation date).
- `repositories.csv`: Includes metadata for each repository, such as the repository's full name, creation date, star count, language, and license type.
## Key Insights and Recommendation
This analysis of Mumbai developers shows a high prevalence of web development projects, suggesting a demand for skills in web-related languages. Therefore, developers interested in gaining traction within the Mumbai tech community might benefit from focusing on JavaScript, Python, and HTML. Also, Java is more popular as compared to C/C++. Regarding developers GitHub profiles, a correlation of −0.391 suggests that longer bios might actually correlate with fewer followers, possibly indicating that users with shorter, more concise bios tend to attract more followers. This finding could mean that followers prefer simpler or more direct descriptions. The positive difference 0.222 implies that hireable users are indeed more likely to provide contact information, which is intuitive since these users may want to make it easy for potential employers or collaborators to reach them.
