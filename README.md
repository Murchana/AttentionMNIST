# AttentionMNIST
AttentionMNIST is a mouse-click attention tracking dataset for handwritten numeral and alphabet recognition introduced in our paper: https://doi.org/10.1038/s41598-023-29880-7 


Multiple attention-based models that recognize objects via a sequence of glimpses have reported results on handwritten numeral recognition. However, no attention-tracking data for handwritten numeral or alphabet recognition is available. Availability of such data would allow attention-based models to be evaluated in comparison to human performance. We collect mouse-click attention tracking data from 382 participants trying to recognize handwritten numerals and alphabets (upper and lowercase) from images via sequential sampling. Images from benchmark datasets are presented as stimuli. The collected dataset, called AttentionMNIST, consists of a sequence of sample (mouse click) locations, predicted class label(s) at each sampling, and the duration of each sampling. 

# Data
Our data consists of a sequence of T=12 episodes for each participant. The data from each episode consists of: (1) the location in the image clicked by the participant (one click in image per episode), (2) the class(es) selected by the participant, and (3) the time taken by the participant to register the current sample (i.e. the time elapsed between the last and current clicks in the image).

Refer to the ReadData.ipynb file for reading the data.


# Citation for using the dataset
Baruah, M., Banerjee, B., Nagar, A. K., & Marois, R. (2023). AttentionMNIST: a mouse-click attention tracking dataset for handwritten numeral and alphabet recognition. Scientific Reports, 13(1), 3305. https://doi.org/10.1038/s41598-023-29880-7 

# Contact
For any questions email: murchanabaruah23@gmail.com
