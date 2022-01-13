1、本项目中，由于没有使用全部的数据集，因此预测时可能会有误差
2、本例程中可以修改的部分：
（1）学习率
optimizer='adam'
（2）损失
loss='sparse_categorical_crossentropy'
（3）训练批次
training_epochs = 3
（4）使用的模型中的可以修改的部分
    x = tf.keras.layers.Flatten()(last)
    x = tf.keras.layers.Dense(128,activation='relu')(x)
    x = tf.keras.layers.Dropout(0.3)(x)
    x = tf.keras.layers.Dense(32,activation='relu')(x)
    x = tf.keras.layers.Dropout(0.3)(x)
    x = tf.keras.layers.Dense(2,activation='softmax')(x)
3、全部的数据集
链接：https://pan.baidu.com/s/1WY717NT4ZdUXvQfKXXCi_g 
提取码：kqgt
