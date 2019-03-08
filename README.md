# ludwig-titanic
jupyter notebook and data for uber's ludwig

I assembled this notebook after reading this article:

https://towardsdatascience.com/introducing-ubers-ludwig-5bd275a73eda

## ludwig repo:
https://github.com/uber/ludwig

## ludwig main doc site:
https://uber.github.io/ludwig/

### Titanic example:
https://uber.github.io/ludwig/examples/#kaggles-titanic-predicting-survivors

### kaggle data:
https://www.kaggle.com/c/titanic/

cmd lines that could be used instead of this notebook
```
ludwig experiment --data_csv train.csv  --model_definition_file model_definition.yaml

ludwig visualize --visualization learning_curves --training_statistics results/experiment_run_0/training_statistics.json
```
