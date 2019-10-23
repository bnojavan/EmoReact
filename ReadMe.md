EmoReact is a multimodal emotion dataset of children between the ages of four and fourteen years old that contains 1102 videos; the biggest dataset of its kind. This dataset is  annotated for 17 affective states, including six basic emotions (happiness, sadness, surprise, fear, disgust, and anger), neutral, valence and nine complex emotions including curiosity, uncertainty, excitement, attentiveness, exploration, confusion, anxiety, embarrassment and frustration.

To obtain the labels in EmoReact, crowd workers from the online crowd sourcing platform, Amazon’s Mechanical Turk (MTurk)  were recruited. Each video was annotated by three independent workers for seventeen labels. The interface for annotations contained the definitions of each label for consistency and as a test of the rater's vigilance and rational decision making a question about the gender of the child in the video was included. All emotions except valence are annotated on a 1-4 Likert scale where 1 shows the absence of emotion and 4 shows the intense presence of the emotion (with 2 and 3 showing little and moderate expression of the emotion). Valence was annotated on a scale from 1-7; representing strongly negative to strongly positive.

The length of these videos are between 3 seconds to 21 seconds with an average length of about 5 seconds. The emotions have been expressed by 63 different children, 32 female and 31 males, with some diversity in ethnicity. 


Visual features are extracted using the open-source tool OpenFace. We selected frames where the faces are successfully detected. Audio features are extracted using COVAREP, with frame length of 10 milliseconds. After extracting the raw features for each frame, we summarize the video for both modalities by computing the mean and standard deviation for all frames and then concatenate them. We are also releasing the featureset with the dataset. 

To request dataset and features please fill out the form here: https://www.behnaznojavan.com/data


