# Spotify Reviews Insights 🎵
The purpose of this analysis is to **identify the most popular words** used in reviews for each star category (1-5, with 1 and 5 being the most important ones). We will also prepare some **basic analysis** to track how the reviews have been changing over the time. The last step is preparing a **machine learning model** and test it on some test data.

## Key insights 🌟
- There is a lot of polarizing reviews, both positive and negatives. Spotify clearly hits the spot with a lot of the users, but there is also a huge group of unsatisfied customers and focusing more on the negatives might give a feedback on what to priortize for fixing/growth.
- A huge spike in negative reviews appeared on April 2022 – tracking the changes to the app that happened around that time would help pinpointing the particular business decision that made a lot of users dissatisfied.
- Analyzing top upvoted reviews overall could also show us some important insight from users

## Machine learning model

             `precision    recall  f1-score   support

    negative       0.75      0.82      0.78      5001
    positive       0.87      0.81      0.84      7318
    accuracy                           0.81     12319
    macro avg      0.81      0.81      0.81     12319
    weighted avg   0.82      0.81      0.82     12319`
