# An investigation into an automatic detection of fake News using extreme gradient boosting approach

## Dataset Used
<a href="https://ieee-dataport.org/open-access/fnid-fake-news-inference-dataset">
    FNID Fake News Inference Dataset
</a>

## Several Classifiers with Annova Test

|Classifiers |Accuracy|CM                    |F1 Score|Precision|Recall|
|-------------|--------|---------------------|--------|---------|------|
|XgBoost      |79.45%  |911 265 <br/> 169 767|80.76%  |84.35%   |77.47%|
|SVM          |77.23%  |875 301 <br/> 180 756|78.44%  |82.94%   |74.40%|
|Logistic Reg |77.70%  |872 304 <br/> 167 769|78.74%  |83.93%   |74.15%|
|Naive Bayes  |69.79%  |743 433 <br/> 205 731|69.96%  |78.38%   |63.18%|

## Several Classifiers without Annova Test
|Classifiers  |Accuracy|CM                   |F1 Score|Precision|Recall|
|-------------|--------|---------------------|--------|---------|------|
|XgBoost      |79.16%  |898 278 <br/> 162 774|80.16%  |84.72%   |76.36%|
|SVM          |76.23%  |859 317 <br/> 185 751|77.39%  |82.28%   |73.04%|
|Logistic Reg |76.33%  |860 316 <br/> 184 752|77.48%  |82.38%   |73.13%|
|Naive Bayes  |71.21%  |778 398 <br/> 210 726|71.90%  |78.74%   |66.16%|
