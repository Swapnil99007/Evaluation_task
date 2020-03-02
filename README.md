**For Step-1 :**
I have used BeautifulSoup for scraping the provided link and downloading the images from it. To make the Image Retrieval task automated according to the Day of Year and Year, two inputs are taken correspondingly.Then I have opened the (.IMG) files using the planetaryimage library and converted them to numpy arrays using the (.image) function. And have plotted the required images.


**For Step-2 :**
In this step, I have downloaded images from 4th June to 6th June of 2011 and labelled them as '1' and have downloaded images of 6th April ,2011 and labelled them as '0'. Then I have made the labelled training and test sets.


**For Step-3 :**
I have trained an SVM Model on the training data and tested them on the test data.