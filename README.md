# LogisticRegression
# First i split my data into "train" and "test" set
# Then using "StandardScaler" i make future scaling """sc.fit_transform(X_train)""" on my "X_train" and "X_test"
# I import "LogisticRegression" and train my set """classifier.fit(X_train, Y_train)"""
# Using my classifier i make predictions """classifier.predict(sc.transform([[30, 87000]]))"""
