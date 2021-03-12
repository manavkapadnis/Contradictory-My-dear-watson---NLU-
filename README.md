# Contradictory-My-dear-watson-NLU
<br>
In this project, we’re classifying pairs of sentences (consisting of a premise and a hypothesis) into three categories - entailment, contradiction, or neutral. Let’s take a look at an example of each of these cases for the following premise:

__sentence__ - He came, he opened the door and I remember looking back and seeing the expression on his face, and I could tell that he was disappointed.


## Hypothesis 1:
<br>
"Just by the look on his face when he came through the door I just knew that he was let down."
<br>
We know that this is true based on the information in the premise. So, this pair is related by __entailment__.
<br>

### Hypothesis 2:
<br>
"He was trying not to make us feel guilty but we knew we had caused him trouble."
<br>
This very well might be true, but we can’t conclude this based on the information in the premise. So, this relationship is __neutral__.
<br>

### Hypothesis 3:
<br>
"He was so excited and bursting with joy that he practically knocked the door off it's frame."
<br>
We know this isn’t true, because it is the complete opposite of what the premise says. So, this pair is related by __contradiction__.
<br>
This dataset contains premise-hypothesis pairs in fifteen different languages, including: Arabic, Bulgarian, Chinese, German, Greek, English, Spanish, French, Hindi, Russian, Swahili, Thai, Turkish, Urdu, and Vietnamese.
<br>

### Files:
- train.csv: This file contains the ID, premise, hypothesis, and label, as well as the language of the text and its two-letter abbreviation
- test.csv: This file contains the ID, premise, hypothesis, language, and language abbreviation, without labels.
- sample_submission.csv: This is a sample submission file in the correct format: id: a unique identifier for each sample label: the classification of the relationship between the premise and hypothesis (0 for entailment, 1 for neutral, 2 for contradiction)
