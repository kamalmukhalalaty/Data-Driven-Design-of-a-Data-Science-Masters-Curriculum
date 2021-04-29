# Data-Driven-Design-of-a-Data-Science-Masters-Curriculum

My personal contribution to the overall project 
- Web scraped linkedin Data Science Job Postings 
- Exploritory Data Analysis was performed on 
  - Data Camp scraped & Coursera scraped data (Scraping done by my colleagues)
    - Extracting popular topics
    
    <img src="https://github.com/kamalmukhalalaty/Data-Driven-Design-of-a-Data-Science-Masters-Curriculum/blob/main/Images/datacamp_skills.png">
    <img src="https://github.com/kamalmukhalalaty/Data-Driven-Design-of-a-Data-Science-Masters-Curriculum/blob/main/Images/coursera_skills.png">
    
  - Scraped job descriptions
    - Extracting important skills mentioned in job postings
    
    <img src="https://github.com/kamalmukhalalaty/Data-Driven-Design-of-a-Data-Science-Masters-Curriculum/blob/main/Images/skills_from_jobs.png">
    
  - Looking at importance via most Frequent Words (Key words) and Bigrams

- Hierarchical clustering of keywords in job posting data to validate important topics:

The following dendrogram was created to to clusters skills based on inter-job description term frequencies or more concretely, which words or groups of words appear most frequently in each job description. The words we chose to analyze are The top 10 most popular general  skills found in job descriptions, And the most popular programming languages and software packages found from analysis of popular coursera courses and job descriptions.

Based on this, the clusters shown on the dendrogram were derived. 

<img src="https://github.com/kamalmukhalalaty/Data-Driven-Design-of-a-Data-Science-Masters-Curriculum/blob/main/Images/dendrogram_1.png">

due to the large amount of terms analysed the dendrogram could be better interpreted by
Zeroing in on the most popular languages and software platforms, 


<img src="https://github.com/kamalmukhalalaty/Data-Driven-Design-of-a-Data-Science-Masters-Curriculum/blob/main/Images/dendrogram_2.png">


Here we see 6 clear clusters and it is nice to see that the clusters make sense. We also see languages like r and c tying into larger clusters that contain more specific skills. 

All in all this reduced dendrogram was very informative and will be used in designing a relevant curriculum for the masters program.
