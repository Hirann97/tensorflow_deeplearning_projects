In this project i'm trying to replicate the deep learning model behind the 2017 paper link text with its 10% of data. The number of RCT papers released is continuing to increase, those without structured abstracts can be hard to read and in turn slow down researchers moving through the literature,so we are creating an NLP model to classify abstract sentences into the role they play (e.g. objective, methods, results, etc) to enable researchers to skim through the literature and dive deeper when necessary.


1.Model-0: Baseline Model

2.Model-1: Conv1D Model

3.preparing datasets for DL model
4.creating coustom text embedding
5.Model-2: Feature extraction Model

6.Model-3: Conv1D with charcter embeddings

7.Model-4: Combining pretrained token Embedings+Charcter embeddings

8.Model-5 Transfer Learning token embeddins +charcter embedding+ positional embedding

9.Creating positional embedding
10.Building the embedded model
11.Model-6: Coustom Token embedded Conv1d+char embedding+ Positional embedding

12.Comparing all the Model results

14.Saving the best performing model

15.Evaluating the mdel with test data

16.Making sample predictions.
