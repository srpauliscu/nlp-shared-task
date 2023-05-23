# SemEval-2023 Task 4: ValueEval

## Summary
Welcome to Spencer Paulissen and Caroline Wendt's shared task repository for the Fall 2022 instance of Natural Language Processing with Dr. Jim Martin at the University of Colorado Boulder. We present a model with these [data](https://zenodo.org/record/6818093#.Y4pqGuzMLIA) for the detection of human values behind arguments to address [Task 4: ValueEval](https://touche.webis.de/semeval23/touche23-web/index.html) in [SemEval 2023](https://semeval.github.io/SemEval2023/).  The task's original repository can be found [here](https://github.com/webis-de/acl22-identifying-the-human-values-behind-arguments).

Data note: The current implementation of our model was developed with the provided training dataset exclusively, prior to the release of the official validation and test datasets.  

## Abstract
Identifying expressions of human values in textual data is a crucial albeit complicated challenge, not least because ethics are highly variable, often implicit, and transcend circumstance. Opinions, arguments, and the like are generally founded upon more than one guiding principle, which are not necessarily independent. As such, little is known about how to classify and predict moral undertones in natural language sequences. Here, we describe and present a solution to ValueEval, our shared contribution to SemEval 2023 Task 4. Our research design focuses on investigating chain classifier architectures with pretrained contextualized embeddings to detect 20 different human values in written arguments. We show that our best model substantially surpasses the classification performance of the baseline method established in prior work. We discuss limitations to our approach and outline promising directions for future work.
