极客杨的OCR工具箱：Tesseract 是目前应用最广泛的免费开源OCR工具（背后有Google的支持）。商业产品有ABBYY的finereader，还有Adobe;国产的有文通和汉王。当前热点是将OCR移植到智能手机上拓展新的输入渠道、IOS有基于Tesseract的实现，Android有高通vuforia API。

识别效率高低的关键还是调参数，主要两点：不同的语言有不同的初始设置； 有颜色或渐进的背景会极大降低识别准确率，需要先转换成黑白／灰度模式（可以试试OpenCV)。 推荐看两篇文章，一篇是Tesseract简介（2007）,另一篇报告了Tesseract在处理彩色图片中遇到的问题。

资料卡片流： http://hao.memect.com/?tag=ocr-tools


[![Tesseract](http://img.memect.com/05jtNcF8k5Kgc3Euvqf5rfZCinM=/400x0/t/1b014ddddc07c435ce3775f3ba85199e706d69456870b9fcb24b5d8ce8c684da)](http://hao.memect.com/?tag=ocr-tools)

# Top Reading - Market Survey
https://tesseract-ocr.googlecode.com/files/TesseractOSCON.pdf  Tesseract features and key issues (2007)

http://www.assistivetechnology.vcu.edu/files/2013/09/pxc3882784.pdf Optical Character Recognition by Open Source OCR 
Tool Tesseract: A Case Study (2012)

http://lifehacker.com/5624781/five-best-text-recognition-tools 

http://www.zhihu.com/question/19593313  

http://www.perfectgeeks.com/list/top-best-free-ocr-software/13

http://lib.psnc.pl/Content/358/PSNC_Tesseract-FineReader-report.pdf  Report on the comparison of Tesseract and 
ABBYY FineReader OCR engines (2012)


# best OCR tools
https://code.google.com/p/tesseract-ocr/  mostly used open source ocr software. apache 2.0. It has been improved extensively by Google

http://finereader.abbyy.com/   one of the best commercial product

http://www.wintone.com.cn/en/  one of the best commercial product for Chinese

# Tesseract in action and Q/A
http://benschmidt.org/dighist13/?page_id=129

http://stackoverflow.com/questions/13511102/ios-tesseract-ocr-image-preperation

http://stackoverflow.com/questions/9480013/image-processing-to-improve-tesseract-ocr-accuracy?rq=1

http://www.sk-spell.sk.cx/tesseract-ocr-parameters-in-302-version



# Tesseract related applications
https://github.com/gali8/Tesseract-OCR-iOS

https://github.com/rmtheis/android-ocr

https://github.com/rmtheis/tess-two


# misc

https://developer.vuforia.com/resources/sample-apps/text-recognition
https://www.youtube.com/watch?v=KLqFQ2u52iU

http://blog.ayoungprogrammer.com/2013/01/equation-ocr-part-1-using-contours-to.html
