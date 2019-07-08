    fourcc = cv2.VideoWriter_fourcc(*'XVID')
    size =(int(cap.get(cv2.CAP_PROP_FRAME_WIDTH )),
            int(cap.get(cv2.CAP_PROP_FRAME_HEIGHT)))
     out = cv2.VideoWriter('output2.avi',fourcc, 20.0,size)
主要使用`videoWriter("name.avi",fourcc,帧率,保存图像大小)`将帧保存为视频，延迟功能使用`time.sleep(seconds)`函数
