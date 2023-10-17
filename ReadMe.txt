程序运行的环境：vscode, Google Colab, windows 10

每个文件的含义：
	①NB.ipynb——NB模型
	②KNN.ipynb——KNN模型
	③LR.ipynb——LR模型
	④bi_lstm_traning.ipynb——BI LSTM模型训练部分的代码
	⑤predict.ipynb——预测部分的代码
	⑥20337188_denglihua.csv——预测部分用
	⑦model文件夹——装载已经训练好的模型

如何复现结果：
	登录Google colab，在“我的云端硬盘”目录内创建两个空文件夹，命名为“ai_lab_final”；
	在“ai_lab_final”文件夹内上传我提交的code文件夹内的model文件夹和predict.ipynb，20337188_denglihua.csv，以及课程网站上提供的train.csv，test.csv；
	返回上一级目录，运行predict.ipynb，之后打开20337188_denglihua.csv便可看到复现出的预测结果