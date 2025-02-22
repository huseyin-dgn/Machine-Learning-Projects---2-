    1. Diabetes Dataset (Frame 1) 🩺
  Description:
This dataset contains medical features used to predict diabetes. The goal is to predict whether a patient has diabetes (outcome 1) or not (outcome 0) based on various medical attributes. 🩻💉

    Used Methods:

Logistic Regression 🧑‍⚕️: A linear classification model used to predict diabetes.

Grid Search 🔎: Used to tune the hyperparameters of the model for better performance.

Decision Tree 🌳: A tree-based model used to classify the data.

K-Nearest Neighbors (KNN) 🏘️: A neighborhood-based classification algorithm.

Random Forest 🌲: A powerful ensemble model based on multiple decision trees.

    Features:
Pregnancies 🤰: Number of pregnancies the patient has had.

Glucose 🍬: Plasma glucose concentration after a 2-hour oral glucose tolerance test.

BloodPressure 💪: Diastolic blood pressure.

SkinThickness 🧴: Skin thickness (in mm).

Insulin 💉: Insulin level after the 2-hour glucose tolerance test.

BMI 🍏: Body Mass Index.

DiabetesPedigreeFunction 👨‍👩‍👧: A function that measures the effect of family history on diabetes risk.

Age 🎂: Age of the patient.

Outcome ✅: Whether the patient has diabetes (1) or not (0).

    2. Housing Price Dataset (Frame 2) 🏠

  Description:
  
This dataset contains features of houses used to predict housing prices. The goal is to predict the median house value based on physical and environmental factors. 🏡💵

    Used Methods:

K-Nearest Neighbors (KNN) 🏘️: A neighborhood-based algorithm used to predict house prices.

Standard Scaler 📏: Used to standardize the features, bringing them to a common scale.

Random Forest 🌲: An ensemble model using multiple decision trees to predict housing prices.

Grid Search 🔍: Used to find the optimal hyperparameters for the models.

    Features:

CRIM 🚔: Crime rate.
ZN 🏞️: Proportion of residential land zoned for large lots.
INDUS 🏭: Proportion of industrial land.
CHAS 🏞️: Charles River proximity (0: not near, 1: near).
NOX 💨: Nitrogen oxide concentrations.
RM 🛏️: Average number of rooms in the house.
AGE 🏚️: Proportion of houses built before 1940.
DIS 🚗: Distance to employment centers.
RAD 🚆: Proximity to radial highways.
TAX 💰: Property tax rate.
PTRATIO 👩‍🏫: Pupil-teacher ratio.
B 👨‍👩‍👧: Proportion of Black population.
LSTAT 💵: Proportion of lower status population.
MEDV 💲: Median house value (in thousands of dollars).

    3. Penguin Dataset (Frame 3) 🐧

  Description:
  
This dataset contains physical characteristics of different penguin species. The goal is to predict the species of a penguin based on its physical traits. 🐦🌍

    Used Methods:

Random Forest 🌲: An ensemble model based on decision trees used to classify penguin species.
Grid Search 🔍: Used for hyperparameter optimization to improve model performance.
Logistic Regression 🧑‍⚕️: A linear model used for classification.
Standard Scaler 📏: Used to standardize features for model efficiency.

    Features:

species 🦜: The species of the penguin (e.g., "Adelie", "Gentoo", "Chinstrap").
island 🏝️: The island where the penguin is found.
culmen_length_mm 🐦: Length of the penguin's bill (in mm).
culmen_depth_mm 🦭: Depth of the penguin's bill (in mm).
flipper_length_mm 🏞️: Length of the penguin's flipper (in mm).
body_mass_g 🏋️‍♂️: Body mass of the penguin (in grams).
sex ⚧️: The sex of the penguin ("MALE" or "FEMALE").
