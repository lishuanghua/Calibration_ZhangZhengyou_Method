1. IR_camera_calib_img文件夹下图片含有畸变，需要得到到相机的内外参数与畸变参数，并对畸变图片做矫正，矫正图片保存在save_dedistortion文件夹下；
2. RGB_camera_calib_img文件夹下图片不含畸变，需要得到到相机的内外参数与畸变参数；
3. 棋盘格规格为：12*9，格点长度0.02m，由于opencv输入参数为内角点个数，所以输入参数为11*8。