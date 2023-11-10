# I310D-Data-Bias-Project

In this project I will be using the Perspective API by Jigsaw to analyze a dataset of toxic comments to determine or prove a hypothesis. In order to analyze the dataset, I will be collecting the toxicity values calculated by Perspective API. The hypothesis that guided my testing was: 

"Perspective API will be less accurate in detecting hate comments that do not contain swear words, and therefore will have increased accuracy in detecting toxic comments with swear words."

The dataset that was used to test my hypothesis had 31 comments. The 31 comments were split into three categories:

1.   Toxic comments that do **not** contain swear words 
2.   Toxic comments that **do** contain swear words
3.   Non-toxic comments that are neutral

The model's accuracy will later be tested by how often it is able to correctly identify the toxicity of a comment. 

After running the comments through the Perspective API and collecting the toxicity scores, the results were:

*   Only 5 out of 13 toxic comments that did **not** contain swear words were correctly identified as toxic 
*   13 out of 13 toxic comments that did include swear words were correctly identified to be toxic
*   5 out of 5 neutral comments were found to be neutral

Insights: 

1.   Toxic hate comments that did **not** contain swear words were less identifiable than their swear word counterpart, as noticeable by the disparity in correct identification of the comments, which was 5/13 being identified versus 13/13. 
2.   This difference in the correct identification of hate comments based on swear words leads me to think that there is a bias in Perspective API that targets comments with swear words, therefore also being able to better identify hate comments with swear words. This may become problematic as a creative commenter can leave a toxic comment but has a better chance to avoid being flagged if they can word their comment without swear words and or be creative with censoring. 

I believe that the results I achieved through testing proves my hypothesis correct as the API was indeed less accurate at detecting toxicity without the presence of swear words. 


