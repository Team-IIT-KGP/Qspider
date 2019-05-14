# Qspider

To reproduce the results in the paper given by `QSpider` simply run `QSpider.ipynb` after cloning this repository.

To train your own Question Type classifier refer to [bert-multiclassifier](https://github.com/kaushaltrivedi/bert-toxic-comments-multilabel)
and [pytorch-pretrained-bert](https://github.com/huggingface/pytorch-pretrained-BERT) and use the appropriate pre-trained BERT model to predict question type and generate the feature matrix,
and finally run `QSpider.ipynb` with proper path set to generate predictions.
