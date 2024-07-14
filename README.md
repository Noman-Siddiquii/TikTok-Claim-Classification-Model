# TikTok-Claim-Classification-Model

## TikTok Video Claim and Opinion Classification

### Overview
This project aims to classify claims and opinions in TikTok videos using various machine learning models. Our goal is to develop a robust model that can accurately classify whether a video contains a claim or an opinion.

### Business Understanding
Classifying claims and opinions in social media content, such as TikTok videos, is crucial for content moderation, misinformation detection, and understanding public sentiment. By accurately identifying claims, TikTok can take appropriate actions to verify the information, while understanding opinions helps in gauging public sentiment and trends.

### Data Understanding
The dataset consists of video information from TikTok, with the following features:
- **claim_status:** Indicates whether the video contains a claim or opinion.
- **video_id:** Unique identifier for the video.
- **video_duration_sec:** Duration of the video in seconds.
- **video_transcription_text:** Text content of the video.
- **verified_status:** Indicates if the user is verified or unverified.
- **author_ban_status:** Indicates if the author is banned, active, or under review.
- **video_view_count:** Number of views of the video.
- **video_like_count:** Number of likes on the video.
- **video_share_count:** Number of shares of the video.
- **video_download_count:** Number of downloads of the video.
- **video_comment_count:** Number of comments on the video.

### Modeling and Evaluation
Several machine learning models were tested to determine the most effective method for classifying claims and opinions in TikTok videos. The chosen models, Random Forest Classifier and XGBoost, demonstrated the best performance in terms of accuracy, precision, recall, AUC, and F1 score.

Key metrics for the Random Forest model are as follows:
- **Accuracy:** 99%
- **Precision:** 99%
- **Recall:** 99%
- **F1 Score:** 99%

### Feature Importance
The plot below shows that in the Random Forest model, video view count, video like count, video share count, video download count, and video comment count have the highest importance. These variables are most helpful in predicting the outcome variable, claim status.
![tik](https://github.com/user-attachments/assets/997b195c-e0de-437a-b363-4f29aa74acda)



### Conclusion
The analysis provides valuable insights into the factors influencing claim and opinion classification in TikTok videos. Key factors include video view count, video like count, video share count, video download count, and video comment count. By leveraging these insights, TikTok can enhance its content moderation and misinformation detection efforts.
