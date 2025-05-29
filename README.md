# Datasets Information

These datasets are made combining a random amount of samples from [CSDMC2010 Spam Corpus](https://github.com/zrz1996/Spam-Email-Classifier-DataSet), [SpamAssassin Public Corpus](https://spamassassin.apache.org/old/publiccorpus/) and [Nazario Phishing Corpus](https://monkey.org/~jose/phishing/). It consists of a total of 5,500 samples and 55% of them are ham.
- `train.csv` has 4,000 samples.
- `val.csv` has 550 samples.
- `test.csv` has 550 samples.

Some preprocessing was applied, like decoding Base64 content, removing as much HTML and noise as possible, extracting only the email body, removing any spam-related tags that would reveal the result, and keeping only the English emails.

⚠️ All copyrights belong to the original authors of the datasets.
