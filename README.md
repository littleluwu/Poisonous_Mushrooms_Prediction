# **🍄 Prediction of Poisonous Mushrooms**

This project aims to predict whether a mushroom is poisonous or edible based on its features. We designed the solutions based on the [Binary Prediction of Poisonous Mushrooms competition](https://www.kaggle.com/competitions/playground-series-s4e8) hosted on **Kaggle**. The Jupyter Notebook in this repository describes the data analysis process, the transformations and cleaning techniques applied, and the training of a classifier model capable of predicting the target class.

## 📂 About the data

The data comes from a deep learning model trained on the UCI Mushroom dataset. The original data from the mushroom dataset and the data provided for the competition have their differences. In the data description, they inform that the data has not been cleaned up for the competition, which implies an additional cleaning process. We observed this during the analysis procedure, where we can observe some corruption in the provided CSV files. In the section detailing the approaches, we describe how we worked around this difficulty.

About the information provided, we have 20 distinct features describing the mushroom:

### General features
- **does-bruise-or-bleed** : bruises (t), no (f)

- **habitat** : grasses (g), leaves (l), meadows (m), paths (p), urban (u), waste (w), woods (d)

- **season** : autumn (a), winter (w), spring (s), summer (u)

- **has-ring** : ring (t), no (f)

- **ring-type** : cobwebby (c), evanescent (e), flaring (f), large (l), none (n), pendant (p), sheathing (s), zone (z)

- **spore-print-color** : black (k), brown (n), buff (b), chocolate (h), green (r), orange (o),purple (u), white (w), yellow (y)

- **veil-type** : partial (p), universal (u)

- **veil-color** : brown (n), orange (o), white (w), yellow (y)

### Cap related features

- **cap-diameter** : 

- **cap-shape** : bell (b), conical (c), convex (x), flat (f), knobbed (k), sunken (s)

- **cap-surface** : fibrous (f), grooves (g), scaly (y), smooth (s)

- **cap-color** : brown (n), buff (b), cinnamon (c), gray (g), green (r), pink (p), purple (u),red (e), white (w), yellow (y)

### Gill related features
- **gill-attachment** : attached (a), descending (d), free (f), notched (n)

- **gill-spacing** : close (c), crowded (w), distant (d)

- **gill-color** : black (k), brown (n), buff (b), chocolate (h), gray (g), green (r), orange (o), pink (p), purple (u), red (e), white (w), yellow (y)

### Stem related features
- **stem-height** :

- **stem-width** :

- **stem-root** : bulbous (b), club (c), cup (u), equal (e),  rhizomorphs (z), rooted (r), missing (?)

- **stem-surface** : fibrous (f), scaly (y), silky (k), smooth (s)

- **stem-color** : brown (n), buff (b), cinnamon (c), gray (g), orange (o), pink (p), red (e), white (w), yellow (y)


## 🔎 The prediction approaches

- Enconding and Cleaning corrupt data - 65% acc

- Feature Selection - N/A% acc

> To be detailed..

## 📑 References

- Walter Reade, Ashley Chow. (2024). Binary Prediction of Poisonous Mushrooms. Kaggle.

- "Mushroom," UCI Machine Learning Repository, 1981. [Online]. Available: https://doi.org/10.24432/C5959T.