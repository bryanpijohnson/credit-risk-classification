# Bryan Johnson's GWU Module 20 - Credit Risk Classification READ ME (and Report) File

## The files for this assignment can be found at the following repo:
https://github.com/bryanpijohnson/credit-risk-classification

## Within the repo link, you will find the following folders and files to be reviewed and graded:

- **README.md** - that is this file :)
    - Inside this file, you will also find the reporting of the analysis. It is at the bottom of the file.
- **Credit_Risk** - this holds the initial CSV file and the report-template we were given to model our own report on
- **credit_risk_classification.ipynb** - this is the file that holds the analysis

## Initial Set Up and Completion

I was able to quickly move through the analysis based on the content from the lessons and the repitition from the activities in each lesson. Having that repetition was actually very beneficial in helping me understand the content.

## REPORTING

### Overview
The purpose of the analysis was to find a model that would predict the likeliness that a loan would default based on certain number of factors, such as `loan_size`, `interest_rate`, `borrower_income`, `debt_to_income`, `num_of_accounts`, `derogatory_marks`, and `total_debt`. The `loan_status` was the target we were trying to predict, with `0` meaning the loan was healthy, and not likely to default, and a `1` meaning the loan was considered high-risk and was likely to default.

### Results
Based on the classification report, the following results were found:
- Accuracy: 99%
- Precision
    - Score = 0 (healthy loan): 100%
    - Score = 1 (at-risk loan): 85%
- Recall
    - Score = 0 (healthy loan): 99%
    - Score = 1 (at-risk loan): 91%

### Summary
Based on the above scores, I would recommend this model. Since the overall accuracy is 99%, this will do a great job of classifying both healthy and at-risk loans. My only note to the stakeholders would be for them to know that with an 85% precision score for at-risk loans, that they may categorize more healthy loans as at-risk, even though the number of at-risk loans is substantially lower.

---

If you have any questions, please feel free to contact me.