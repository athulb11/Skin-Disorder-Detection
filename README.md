# Skin-Disorder-Detection
## Problem Statement

Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a predictive model  using machine learning techniques to predict the various classes of skin disease. 

Task3:-Suggestions to the Doctors to identify the skin diseases of the patient at the earliest. 

## Dataset Information:
This database contains 34 attributes, 33 of which are linear valued and one of them is nominal.The differential diagnosis of erythemato-squamous diseases is a real problem in dermatology. They all share the clinical features of erythema and scaling, with very little differences. The diseases in this group are psoriasis, seboreic dermatitis, lichen planus, pityriasis rosea, cronic dermatitis, and pityriasis rubra pilaris. Usually a biopsy is necessary for the diagnosis but unfortunately these diseases share many histopathological features as well. Another difficulty for the differential diagnosis is that a disease may show the features of another disease at the beginning stage and may have the characteristic features at the following stages. Patients were first evaluated clinically with 12 features. Afterwards, skin samples were taken for the evaluation of 22 histopathological features. The values of the histopathological features are determined by an analysis of the samples under a microscope.In the dataset constructed for this domain, the family history feature has the value 1 if any of these diseases has been observed in the family, and 0 otherwise. The age feature simply represents the age of the patient. Every other feature (clinical and histopathological) was given a degree in the range of 0 to 3. Here, 0 indicates that the feature was not present, 3 indicates the largest amount possible, and 1, 2 indicate the relative intermediate values.The names and id numbers of the patients were recently removed from the database.

## CONCLUSION:-
In the field of dermatology, differential diagnosis of Erythmato-Squamous Diseases (ESD) is difficult. The six important types of ESD are including psoriasis, seborrheic dermatitis, lichen planus, pityriasis rosea, chronic dermatitis and pityriasis rubra pilaris.

1. The dataset contains 366 rows and 35 columns in which 12 features are clinically evaluated first and rest 23 are found by taking the skin samples.
   
2.There was no null values but Age attribute had some wrong value "?" and also age attribute had 0 as a value which is not possible thus we changed the wrong value and replaced the 0 value with the mean.

3.While checking the correlation of these attributes it is seen that many attributes have high accuracy which was leading for overfitting and thus we changed those as well.The dropped attributes are itching,koebner_phenomenon,polygonal_papules,oral_mucosal_involvement, melanin_incontinence,eosinophils_in_the_infiltrate, acanthosis, hyperkeratosis, focal_hypergranulosis, vacuolisation_and_damage_of_basal_layer, saw-tooth_appearance_of_retes,inflammatory_monoluclear_inflitrate,band-like_infiltrate.

4.We had used 5 Machine Learning Algorithms -Decision Tree,Random Forest,SVM,XG-Booster,Logistic Regression.

5.From these Decision Tree showed an accuracy of 93%,Random Forest showed an accuracy of 93%,SVM has92%,XG-Booster has 93%,Logistic Regression has 92%.

6.From these Random Forest was used for prediction and it showed the correct disease from the 6 diseases.

### SUGGESTION:-
Early detection is the best prevention.Both clinical and histopathological analysis is required for the detection.Eventhough our model gives accurate prediction of the disease it is also required to examine under a specialist Doctor.In this model we had only used 22 attributes for prediction which can make the detection faster with the help of a specialist doctor.

### RISKS:-
Since all of the attributes are from medical domain it was difficult to learn about them and find the insights.But later we got familiar with them and found all the insights.
