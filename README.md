# Log Anonymization 🛡️

**Approaches Used**

For this challenge I have used two approaches, firstly I have done a simple non-NLP approach of hiding PIIs to gain intuition on the project, I have simply identified the PIIs, and hidden them by using X symbols.

*Output Validation:*

![image](https://github.com/Tavleen1203/LogAnonymization_Challenge/assets/122363068/3401ab7f-16d3-48a5-8d13-56a2bb4cdd28)

Next, after gaining sense of the implementation I have moved to the NLP Code, the technique that I used here was text masking. For this, I have created a sensitive_info object, for reference. Then upon iterating over the data, each time a pattern of the object is encountered, the mask_text() function is called and it masks the text based on tag defined in the sensitive_info.

*Output Validation:*

![image](https://github.com/Tavleen1203/LogAnonymization_Challenge/assets/122363068/5f716e67-09f1-43ca-9d65-390e7293ddb9)

Notebook:
https://colab.research.google.com/drive/1jWk8vRdwCptGgVWXPYhK0MG9Fbk2xsuW?usp=sharing

