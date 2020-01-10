ndk 16
android studio 3.5.3
//缩减了opencv的库，暂未发现问题

#存在问题
有时退出activity时会jni报错，待排查(未知是否因为缩减了opencv而导致的)(猜测是退出activity时未释放c++的空色框，即jniDeInit未释放完成)