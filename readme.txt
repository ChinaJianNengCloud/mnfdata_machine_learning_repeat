#文章内容
如何用小样本学习建立HIV合并马尼肺感染患者的疾病筛选模型

#数据内容
数据名称为:归一化后的数据.xlsx
其中内有4个表，分别是训练集，留出集，西溪验证集，浙一验证集
每个表中第一列group为标签，其余列为自变量

#项目内容
本项目为复现用机器学习模型进行分类的项目
其中AUC_train_test3.7_21.51-lh.ipynb是娄工的代码
其中AUC_train_test3.7_21.51-yinda-cv.ipynb是陈胤达的代码
进行了3个修改，1.增加了单纯的训练集，因为他原本的训练集是训练集进行交叉验证得到的auc，2.增加了CalibratedClassifierCV校验，3.所有的模型都用predict_proba正类概率计算auc
其中AUC_train_test3.7_21.51-yinda-nocv.ipynb是陈胤达的代码，是没有添加cv校验

#项目结果
其中AUC汇总3月22日14时36分.xlsx是娄工的结果
其中机器学习复现yinda.xlsx是陈胤达的结果