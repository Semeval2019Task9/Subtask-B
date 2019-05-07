# Semeval 2019 Task 9 - SubTask B - Suggestion Mining from Online Reviews and Forums

This repository contains the data as well as the scripts for SubTask B of the Semeval 2019 Task 9 competition.

You can access the Codalab competition here: https://competitions.codalab.org/competitions/19956 

Discussions and questions regarding this competition can be found here: https://groups.google.com/d/forum/semeval-2019-task-9 

## Getting Started

You can download or clone this repository to retrieve all required information. 

* Filename_Training.csv contains the training data. Please use the most recent versions for final submissions.

* Filename_Trial_Test.csv contains the trial test data which is required to trial test your results on Codalab. You can also use this dataset as the validation dataset for your final submission, when a new test dataset would be provided. It is structured in the three columns "id, sentence, prediction" whereby prediction is set as "X". Your task is to replace all X with the respective prediction for each sentence. DO NOT add any additional row, like the header row, to the prediction file.

* SubtaskB_EvaluationData.csv contains the final evaluation data. Similar to the trial phase, it is structured in three columns <id>, <sentence>, <prediction> whereby prediction values are set as "X". Your task is to replace all Xs with the respective prediction for each sentence. DO NOT add any additional row, like the header row, to the prediction file. 
Prediction file should be named as 'submission.csv', zipped and named as submission.csv.zip, and uploaded on CodaLab.

### Prerequisites

Python 2.7 is required to run the evaluation_script.py

## Citing Semeval 2019 - Task 9

Please cite the following paper when using our resources: 

```
@inproceedings {negi2019semeval,
  author={Negi, Sapna and Daudert, Tobias and Buitelaar, Paul},
  booktitle={Proceedings of the 13th International Workshop on Semantic Evaluation (SemEval-2019)},
  title={SemEval-2019 Task 9: Suggestion Mining from Online Reviews and Forums},
  pages={783--883},
  year={2019}
}
```

### License

All resources provided in this repository are licensed under the Creative Commons Attribution-Non-Commercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license [1].

[1] https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode
