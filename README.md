在esp-player-sink中，板子接收到中麦克风的pcm数据，编码成opus帧，通过socket发送给电脑端。在audiostram-host中，电脑端接收到opus帧，解码成pcm，保存在文件中。
