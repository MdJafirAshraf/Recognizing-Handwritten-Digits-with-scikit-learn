# Recognizing-Handwritten-Digits-with-scikit-learn

##  Introduction:

Recognizing handwritten text is a problem that can be traced back to the first automatic machines that needed to recognize individual characters in handwritten documents. 
Classifying handwritten text or numbers is important for many real-world scenarios. 
For example, a postal service can scan postal codes on envelopes to automate the grouping of envelopes which has to be sent to the same place. 
This article presents recognizing the handwritten digits (0 to 9) using the famous digits data set from **Scikit-Learn**, using a classifier called **Support Vector Machine**.

## Recognizing Handwritten Digits with Scikit-learn:
Scikit-learn provided multiple Support Vector Machine classifier implementations. 
SVC supports multiple kernel functions (used to split with non-linearly) but the training time complexity is quadratic with the number of samples. 
Multiclass classification is done with a one-vs-one scheme. On the other hand, LinearSVC only supports linear kernels but the training time is linear with the number of samples. 
The multiclass classification is done with a one-vs-others scheme.

