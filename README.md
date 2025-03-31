This is the README for Module 17.

Please see prompt_III.ipynb for the relevant code and commentary.

A discussed further in that file, we have a preliminary predictive algorithm based on a K-Nearest Neighbors (KNN) analysis. It yields a precision of ~45%, meaning that the customers the model predicted would say "yes," about 45% actually did. So, more than half of the outreach may not lead to conversions — still better than guessing, but room to improve. It yields a recall of ~25%, meaning that out of all the customers who actually said "yes," the model correctly found only about 1 in 4 of them. That means it's missing many potential successes. That in turn means that, though this model would provide good guidance in prioritizing marketing, we should not let it act as a total guide of all marketing.
The factors that had the greatest influence on success were:
	•	Whether prior marketing succeeded with the customer, which makes intuitive sense.
	•	The number of days since the last contact.
	•	The month of the contact. In particular, the sping and fall saw the most success.
	•	The job of the target. Students and retired people were most receptive.
