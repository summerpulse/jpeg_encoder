jpeg_encoder
============

压缩bmp图像至jpg文件中
这个工程师为我的博客中的一个系列文章准备的 
http://thecodeway.com/blog/?p=69
目的是为了解释jpeg压缩算法的过程，所以没有考虑优化，速度奇慢，只可用来学习，不建议用在实际项目中

使用方法

	JpegEncoder encoder;
	//输入文件必须是24bit的BMP文件
	encoder.readFromBMP(inputFileName);
	encoder.encodeToJPG(inputFileName, 50);
