# Module_21_Deep_Learning_Challenge
Module_21_Deep_Learning_Challenge

Overview:
The purpose of this analysis was to take a look at all of the different applications and their ventures and see if we are able to start predicting if they would be successful or not using the older data sets that we currently have.  We looked at the different factors including the type of application, affiliation, classification, the use case, organization type, status, income, any special considerations, and the ask amount to see if their ventures were successful. 

Result:
The target for this model was the is succesful category.  The variables that were used as festures were type of application, affiliation, classification, the use case, organization type, status, income, any special considerations, and the ask amount.  We removed the name of the organization and the EIN number since they have no reason to be added onto the features.  They have no value and should have no difference what they are to effect the outcome.  WE ended up using 300 neurons on the first layer and 200 neurons on the second layer since out of the different tries that I worked on this was the best.  
I was not able to achieve the target model performance even after adding a third hidden layer and changing the neurons multiple times.  We also used different calculating techniques such as sigmoid, tanh, and relu.  

summary:
I can assume that with this model, we coudl not get over 75% accuracy and I do not recomend using this model.  We could look at possibly a non binary model that could better look at the outlook if we were able to show how close to being successful it was.  
