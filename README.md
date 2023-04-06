# LogisticRegression
# First i split my data into "train" and "test" set
# Then using "StandardScaler" i make future scaling """sc.fit_transform(X_train)""" on my "X_train" and "X_test"
# I import "LogisticRegression" and train my set """classifier.fit(X_train, Y_train)"""
# Using my classifier i make predictions """classifier.predict(sc.transform([[30, 87000]]))"""
# Then i make my "Y_pred" """classifier.predict(X_test)""" 
# I change my results into columns """np.concatenate((Y_pred.reshape(len(Y_pred),1), Y_test.reshape(len(Y_test),1)),1)"""
# Next i import "confusion_matrix" and put into it my "Y_test" and "Y_pred", I check the results
