鸢尾花分类:


关键代码：大写字母二维整数，小写表一个对象标签

X_train,X_test,y_train,y_test = train_test_split(iris_dataset['data'],iris_dataset['target'],random_stat=0)
knn=KNeighborsClassifier(n_neighbor=1)

knn.fit(X_train,y_train)

print("test set score:{:.2f}'.format(knn.score(X_test,y_test)))

