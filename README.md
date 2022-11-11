! pip install sklearn
from sklearn import tree
x = [[0,0],[1,1]] # example let's suppose that it's the inbox
y = [0,1] # example let's suppose that  it's the spam
clf = tree.DecisionTreeClassifier()
clf = clf.fit(x,y)
clf.fit(x,y)
clf.predict([[1.,1.]]) # predicting data
