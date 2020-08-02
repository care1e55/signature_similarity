# Signature simularity
Jupyter ноутбук с baseline решением Signature simularity на датасете [signature-verification-dataset](https://www.kaggle.com/robinreni/signature-verification-dataset)

[Оригинальная статья](https://arxiv.org/pdf/1707.02131.pdf)

Boilerplate код взят с публичного кернела [kaggle](https://www.kaggle.com/robinreni/signature-classification-using-siamese-pytorch)

Архитектура siamese с resnet18 для получения глубоких фичей.

Accuracy и f1 на тестовом датасете: 0,92

### TODO:
 - [ ] train/test split
 - [ ] вариации train/test - те что модель видела, те что не видела из тех классов что есть, те что модель невидела никогда  
 - [ ] Gridsearch границы forged/original
 - [ ] tiplet loss
 - [x] concat datasets

