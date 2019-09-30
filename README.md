鸢尾花分类:


大写字母表二维数组，小写字母表单个标签，y=f(x)

X_trai,X_test,y_train,y_tes = train_test_split(iris_dataset['data'],iris_dataset['target'],random_stat=0)
knn=KNeighborsClassifier(n_neighbor=1)

knn.fit(X_train,y_train)

print("test set score:{:.2f}'.format(knn.score(X_test,y_test)))

