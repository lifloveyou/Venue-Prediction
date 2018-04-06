# Venue-Prediction
#### Venue Prediction with bag-of-words + heterogenous information as features using sklearn SGDClassifier
## <br> Pipeline:
<br> python ./src/clean_data.py --input ./input/training.txt --output ./input/cleaned_training.txt
<br> python ./src/create_data_example.py --train ./input/cleaned_training.txt --validation ./input/cleaned_validation.txt
<br> python ./src/train_classifier.py --train ./input/cleaned_training.txt --validation ./input/cleaned_validation.txt
