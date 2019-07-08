    fourcc = cv2.VideoWriter_fourcc(*'XVID')//定义视频编码器
    size =(int(cap.get(cv2.CAP_PROP_FRAME_WIDTH )),
            int(cap.get(cv2.CAP_PROP_FRAME_HEIGHT)))
     out = cv2.VideoWriter('output2.avi',fourcc, 20.0,size)
主要使用`videoWriter("name.avi",编码器,帧率,保存图像大小)`将帧保存为视频，延迟功能使用`time.sleep(seconds)`函数

![](http://ww1.sinaimg.cn/large/006YKa8tly1g4skm1oa9tg30ot0dce88.gif)
![](http://ww1.sinaimg.cn/large/006YKa8tly1g4skouwf7lg30ot0dce88.gif)
