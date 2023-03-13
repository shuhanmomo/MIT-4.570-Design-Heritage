# MIT-4.570-Design-Heritage
This is the repository where I will update my ongoing projects in the course MIT 4.570
  
## Image Segmentation -- Decoding the Scene Atmosphere in Movies
  
### Project Statement
This study aims to examine the question how the physical spaces and environments in movies impact the narrative and emotional content of the scenes. Using semantic 
segmentation techniques, the study analyzes the proportion of architectural and natural elements in film sets and categorize the scenes into four emotional 
categories: Sad, Happy, Romantic, and Calm. By creating segmentation diagrams and decoding the design elements of movie sets, this study explores the influence of 
architecture and natural elements on scene atmosphere and storytelling,and contribute to our understanding of the role of these elements inshaping our emotional 
experiences of film.
  
This can be particularly useful for film makers and set designers, who can use this information to create specific atmospheres and moods in their scenes, and for 
film studies researchers, who can use this information to understand the impact of architectural design on the emotional content of films.

### Workflow
**Webscraping**  
- 'Selenium_login.py' is for scraping down corresponding movie shots under each category from an online tool  
![scraped images](https://github.com/shuhanmomo/MIT-4.570-Design-Heritage/blob/cd693d93ce010c18932c2a4cf1fb75f1c038d96e/img/webscraping.jpg)
  
**Image Segmentation**:  
- 'DPT_Segmentation.zip' contains all the inputs and pretrained DPT model, needs to be uploaded to the google drive and copy corresponding path  
- 'Tracy_segmentation.ipynb' is a copy of google collab file which fits the input images into DPT model and out put segmented results and CSV file
![segmentation](https://github.com/shuhanmomo/MIT-4.570-Design-Heritage/blob/cd693d93ce010c18932c2a4cf1fb75f1c038d96e/img/segmented.png)
  
**Data Visualization**:  
- 'pie chart.py' 'histo.py''distribution.py' uses Matplotlib to visualize the exported CSV data
![analysis](https://github.com/shuhanmomo/MIT-4.570-Design-Heritage/blob/cd693d93ce010c18932c2a4cf1fb75f1c038d96e/img/data%20analysis.jpg)

  




