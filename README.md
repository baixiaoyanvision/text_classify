# text_classify
以复旦中文文本分类语料库为样本，用python实现的文本分类算法

给出了训练集和测试集，以及停用词表hlt_stop_words.txt

Python版本为2.7 

运行顺序：
step1：corpus_segment.py

step2: corpus2Bunch.py (需要提前创建目录train_word_bag和test_word_bag)

step3: TFIDF_space.py

step4:NBayes_Predict.py
