## 利用PyPDF2去除扫描全能王水印
> 删除原理：扫描全能王水印有一个二维码(图片)和一串文本`扫描全能王 创建`，设置了一些条件，检出并删除了这两个对象，实现了水印的去除。
1. 用pip安装PyPDF2库,`pip install pypdf2`
2. 修改`input_file`和`output_file`的值，`input_file`为需要去除水印的pdf文件路径，`output_file`为去除水印之后的pdf文件的输出路径
3. 运行程序获得无水印pdf文件
