# Consumer-Complaints-Resolution

Problem statment:
-----------------

Consumer complaint resolution is important to any business. In this particular case we have been given detailed consumer complaints along with whether consumer disputed with the conclusion. If we are able to predict this,consumer who is more likely to dispute a conclusion can be given more attention as to how the complaints are handled as well as how persuasively the final conlusions are conveyed to them.

Initial proposal for solution:
------------------------------

Built Logistic Regression model as the initial step could not get good performance. 

Problems Faced:
---------------

Problem was with the data preperation. Took much time to complete this.

Experiments :
-------------

After Logistic Regression Model, tried Decision Trees also did not,gave good performance but the problem was over fitting. 

Went through Random Forest to overcome over fitting still did not get adequate performance. 

Finally XGBoost came to rescue.


Performance:
------------

Final roc_auc_score is 0.61.
