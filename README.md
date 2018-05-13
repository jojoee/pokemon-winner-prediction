# Pokemon Winner Prediction

Based on [Pokemon- Weedle's Cave | Kaggle](https://www.kaggle.com/terminus7/pokemon-challenge), [result](https://github.com/jojoee/pokemon-winner-prediction/blob/master/pokemon-winner-prediction.ipynb)

## Getting started

1. Install `Python3`
2. Install dependencies and `jupyter`

## TODO / Future improvement

- [ ] Add `requirements.txt`
- [ ] Fix warnings
- [ ] Check more about model evaluation
- Data preparation
  - [ ] Try remove row that contain `NaN` instead of filling it
  - [ ] Try other interpolation methods
  - [ ] Try to normalize data before create model
  - [ ] Try other feature extractions e.g. type-advantage, type1, type2
  - [ ] Try remove Pokemon that have low number of fights
  - [ ] Using "diff" stat instead of raw stat, check https://www.kaggle.com/vforvince1/visualizing-data-and-predicting-pokemon-fights
- Model
  - [ ] Deep learning approach
  - [ ] XGBClassifier
  - [ ] Others e.g. GradientBoostingClassifier, svm
  - [ ] Hyper parameters e.g. distance method, measure method in kNN
- [ ] Demo page
- [ ] Add Pokemon image to demo page

## Ref

### kaggle.com
- https://www.kaggle.com/ndrewgele/visualizing-pok-mon-stats-with-seaborn
- https://www.kaggle.com/algorlabs/got-to-analyse-em-all
- https://www.kaggle.com/athenalog/data-analysis-and-visualization-poke-master
- https://www.kaggle.com/arihantkumarjain/pokemon-analytics
- https://www.kaggle.com/edword/stats-comparison-3d-scatter-plot
- https://www.kaggle.com/casuru/pokemon-analysis
- https://www.kaggle.com/sanghan/first-gen-pokemon-stats
- https://www.kaggle.com/ash316/learn-pandas-with-pokemons
- https://www.kaggle.com/nemo22/data-sciencetutorial-for-beginners
- https://www.kaggle.com/kanncaa1/data-sciencetutorial-for-beginners
- https://www.kaggle.com/rautaki0127/pokemon-data-science-challenge
- https://www.kaggle.com/vedranium/who-s-that-pokemon
- https://www.kaggle.com/rtatman/which-pokemon-win-the-most
- https://www.kaggle.com/kremijowo/learn-machine-learning-for-newbie-in-progress
- https://www.kaggle.com/paulhendi/pokemon-dataset-random-forest-prediction
- https://www.kaggle.com/cookiehunter/battle-outcome-prediction
- https://www.kaggle.com/karenfang/ds-step-by-step-using-pokemon-dataset
- https://www.kaggle.com/vforvince1/visualizing-data-and-predicting-pokemon-fights
- https://www.kaggle.com/hiteshp/r-to-python-tutorial
- https://www.kaggle.com/jonathanbouchet/pokemon-battles
- https://www.kaggle.com/aagundez/pikachu-vs-bulbasaur-matchup,  radar chart
- https://www.kaggle.com/gracezhou0912/analysis-on-pokemon-features
- https://www.kaggle.com/strakul5/principal-component-analysis-of-pokemon-data
- https://www.kaggle.com/galbiati/checking-out-kaggle-nb-with-pokemon-dataset

### Others
- https://seaborn.pydata.org/
- https://seaborn.pydata.org/tutorial/distributions.html
- https://seaborn.pydata.org/generated/seaborn.distplot.html
- https://seaborn.pydata.org/generated/seaborn.countplot.html
- https://pokemondb.net/pokedex/all
- https://bulbapedia.bulbagarden.net/wiki/List_of_Pok%C3%A9mon_by_National_Pok%C3%A9dex_number
