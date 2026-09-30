# 🏥 Personalized Healthcare & Medicine Recommendation System

An AI-powered healthcare assistant that allows users to input symptoms and receive **disease predictions**, **dietary advice**, and **personalized workout plans** using machine learning models.

🔐 Features user **login and signup** functionality for secure access, built using **Flask**, and stores data using **Flask-SQLAlchemy**.

🚀 **Live Demo** : 

---
## 🚀 Key Features

✅ **User Authentication**  
- Secure login/signup using `bcrypt` password hashing

✅ **Symptom-based Disease Prediction**  
- Users enter symptoms, and the ML model predicts the most probable disease
- 
✅ **Medicine Recommendations**  
- Based on predicted illness, suitable medicines are provided

✅ **Diet Recommendations**  
- Based on predicted illness, suitable food and nutrition tips are provided

✅ **Workout Suggestions**  
- Light, moderate, or intense workouts based on user health condition

✅ **Clean Dashboard Interface**  
- Built using Flask templates and styled with Bootstrap for responsiveness.

---

## 🧠 Tech Stack

**Frontend:**
- HTML, CSS

**Backend:**
- Python
- Flask
- Flask-SQLAlchemy
- Flask-Bcrypt

**Machine Learning:**
- scikit-learn
- pandas
- numpy

**Hosting:**
- Render
---

## 📦 Requirements

Create a `requirements.txt` with the following content:

```
Gunicorn
bcrypt==4.3.0
Flask==3.1.0
Flask-Bcrypt==1.0.1
Flask-SQLAlchemy==3.1.1
matplotlib==3.10.0
numpy==2.0.2
pandas==2.2.3
scikit-learn==1.6.0
seaborn==0.13.2
SQLAlchemy==2.0.39

````

Install with:
```bash
pip install -r requirements.txt
````

---

## 🗂️ Project Structure

```
personalized-healthcare-system/
├── app.py                           # Flask application entry point
├── templates/                       # HTML templates
├── static/                          # CSS and images
├── model/                           # ML model files and pickle files
├── dataset/                         # CSV dataset(s) for training
├── instance/                        # Local DB (SQLite)
├── __pycache__/                     # Python cache
├── Medicine_Recommendation_System.ipynb  # Training notebook
├── requirements.txt
└── README.md
```

---

## 💻 Running the App Locally


 Install dependencies:

```bash
pip install -r requirements.txt
```

 Run the app:

```bash
python app.py
```

```

---

## 🧪 ML Workflow Summary

* Input: Symptom list from the user like ( headache , cough)
* Processing: Symptom encoding + prediction using trained model
* Output:
  * Predicted Disease
  * Recommended Exercises
  * Suggested Diet Plan

 project has 132 symptom/features in dataset/Training.csv.

Here is the complete list:
You can search any symptoms 
itching
skin_rash
nodal_skin_eruptions
continuous_sneezing
shivering
chills
joint_pain
stomach_pain
acidity
ulcers_on_tongue
muscle_wasting
vomiting
burning_micturition
spotting_ urination
fatigue
weight_gain
anxiety
cold_hands_and_feets
mood_swings
weight_loss
restlessness
lethargy
patches_in_throat
irregular_sugar_level
cough
high_fever
sunken_eyes
breathlessness
sweating
dehydration
indigestion
headache
yellowish_skin
dark_urine
nausea
loss_of_appetite
pain_behind_the_eyes
back_pain
constipation
abdominal_pain
diarrhoea
mild_fever
yellow_urine
yellowing_of_eyes
acute_liver_failure
fluid_overload
swelling_of_stomach
swelled_lymph_nodes
malaise
blurred_and_distorted_vision
phlegm
throat_irritation
redness_of_eyes
sinus_pressure
runny_nose
congestion
chest_pain
weakness_in_limbs
fast_heart_rate
pain_during_bowel_movements
pain_in_anal_region
bloody_stool
irritation_in_anus
neck_pain
dizziness
cramps
bruising
obesity
swollen_legs
swollen_blood_vessels
puffy_face_and_eyes
enlarged_thyroid
brittle_nails
swollen_extremeties
excessive_hunger
extra_marital_contacts
drying_and_tingling_lips
slurred_speech
knee_pain
hip_joint_pain
muscle_weakness
stiff_neck
swelling_joints
movement_stiffness
spinning_movements
loss_of_balance
unsteadiness
weakness_of_one_body_side
loss_of_smell
bladder_discomfort
foul_smell_of urine
continuous_feel_of_urine
passage_of_gases
internal_itching
toxic_look_(typhos)
depression
irritability
muscle_pain
altered_sensorium
red_spots_over_body
belly_pain
abnormal_menstruation
dischromic _patches
watering_from_eyes
increased_appetite
polyuria
family_history
mucoid_sputum
rusty_sputum
lack_of_concentration
visual_disturbances
receiving_blood_transfusion
receiving_unsterile_injections
coma
stomach_bleeding
distention_of_abdomen
history_of_alcohol_consumption
fluid_overload.1
blood_in_sputum
prominent_veins_on_calf
palpitations
painful_walking
pus_filled_pimples
blackheads
scurring
skin_peeling
silver_like_dusting
small_dents_in_nails
inflammatory_nails
blister
red_sore_around_nose
yellow_crust_ooze

## 🔒 Security Notes

* User credentials are hashed using `bcrypt` for secure storage
* Uses Flask's built-in session management for user sessions

---

## 👨‍⚕️ Author

Developed by Kunal Deshmukh
For educational purposes — AI for social impact in healthcare.
