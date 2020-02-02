# Nairobi Hospital hypothyroidism clinical camp test
Build a model that decides if the patient's symptoms suggest hypothyroidism.

Part 1

Build a model to assess if the patient's symptoms mean the patient has hypothyroid or not. Take advanced models of at least 2 out of 3: random forests, Ada boosted trees, and gradient boosted trees.

Seek to optimize each of the two models, making sure you record how the hyperparameters are configured.

Identify which of the 2 models you have the most confidence in, and use your choice to de

Part 2

Report on the data every transformation you made.

Apply the function Polynomial, linear and rbf kernel to construct your SVM model and then evaluate its output and select the kernel that performs best. Please remember to change your parameters to boost your model's efficiency. Make sure to imagine the templates you've developed to make your life easier. Use any two functions to build the models

Hint: You may want to use decision trees to give you the most preferable features you can use. but also keep in mind that those features might not be suitable for SVM. It might be a good idea to graph them first.

After getting your best performing kernel, use this kernel together with your tuned parameters and repeat the prediction but this time using additional features. Compare the model you've just created with the 2-features version.
