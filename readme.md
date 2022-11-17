# PlayAudioTest
mediaplayer 多媒体播放的使用

#### `MediaPlayer`的工作流：

1. 创建一个`MediaPlayer`对象；

2. 调用`setDataSource()`方法设置音频文件的路径；

3. 再调用`prepare()`方法使`MediaPlayer`进入准备状态；

4. 调用`start()`方法就可以开始播放音频了；

5. 调用`pause()`方法就会暂停播放；

6. 调用`reset()`方法就会停止播放。