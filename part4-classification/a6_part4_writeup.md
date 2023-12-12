# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
The model becomes less accurate than if the program had the StandardScaler because the data isn't equally weighted. One part of the data will end up skewing the results which makes the actual prediction less accurate than the actual value.

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
The accuracy of the model with the StandardScaler tends to be around the range of .45 and .47 which is more accurate than the model without the scaler by about a couple percentage points. I wouldn't say that the model is accurate enough. Although the data is scaled to be weighted the same, the accuracy of the model tends to be less than 50% which is still not a very great percentage if you are trying to make a prediction.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
Looking at the results, it looks like the model didn't do too bad in its predictions. There wasn't very much of a pattern that I could see beside the model being correct 3-4 times and then being wrong for 1-2 times and it continued to repeat in this type of way. Of course there were some exceptions where it was wrong 4-5 times or correct only 1-2 times which makes the pattern listed in the previous sentence not seem correct. The point is that there wasn't much of a visible pattern that I saw.

4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
No, a 34 year old female who has a salary of 56000 a year would be likely to not buy an SUV based on the model. The predicted value given is around 0.372 which is way below the 50% range.
