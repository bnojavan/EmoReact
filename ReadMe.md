<img width="900" alt="Emoreact" src="https://user-images.githubusercontent.com/10718277/170186386-bb9ff542-d3a4-43c8-ac8d-feb5a7efd81d.png">
EmoReact is a multimodal emotion dataset of children between the ages of four and fourteen years old that contains 1102 videos; the biggest dataset of its kind. This dataset is  annotated for 17 affective states, including six basic emotions (happiness, sadness, surprise, fear, disgust, and anger), neutral, valence and nine complex emotions including curiosity, uncertainty, excitement, attentiveness, exploration, confusion, anxiety, embarrassment and frustration.

To obtain the labels in EmoReact, crowd workers from the online crowd sourcing platform, Amazon’s Mechanical Turk (MTurk)  were recruited. Each video was annotated by three independent workers for seventeen labels. The interface for annotations contained the definitions of each label for consistency and as a test of the rater's vigilance and rational decision making a question about the gender of the child in the video was included. All emotions except valence are annotated on a 1-4 Likert scale where 1 shows the absence of emotion and 4 shows the intense presence of the emotion (with 2 and 3 showing little and moderate expression of the emotion). Valence was annotated on a scale from 1-7; representing strongly negative to strongly positive.

The length of these videos are between 3 seconds to 21 seconds with an average length of about 5 seconds. The emotions have been expressed by 63 different children, 32 female and 31 males, with some diversity in ethnicity. 

Visual features are extracted using the open-source tool OpenFace. We selected frames where the faces are successfully detected. Audio features are extracted using COVAREP, with frame length of 10 milliseconds. After extracting the raw features for each frame, we summarize the video for both modalities by computing the mean and standard deviation for all frames and then concatenate them. We are also releasing the featureset with the dataset. 

**EmoReact: A Multimodal Approach and Dataset for Recognizing Emotional Responses in Children** : http://multicomp.cs.cmu.edu/wp-content/uploads/2017/09/2016_ICMI_Nojavanasghari_Emoreact.pdf

**EmoReact is available to public for research purposes**. To get access to data please fill out End-User License Agreement. After receiving your request form, we will get back to you by login information. Please make sure to use academia/industry affiliated email in filling out the form. Data cannot be released to personal accounts. Please allow at least one week for your request to be processed. 

EULA form: https://docs.google.com/forms/d/1Pk7I9mIUBItVKrhZDM0grbucS0wnJ33zXbyisyNdso8/edit?usp=forms_home&ths=true

