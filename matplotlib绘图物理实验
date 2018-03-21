import matplotlib.pyplot as plt
import matplotlib
import xlrd
book = xlrd.open_workbook(r'C:\Users\XX、na\Documents\Tencent Files\1830413177\FileRecv\2.xls')#读入excel数据文件
sheet = book.sheet_by_name('Sheet1')#表格1
x_list=sheet.col_values(0)
y_list=sheet.col_values(1)
matplotlib.rcParams['font.family']='SimHei'#字体设置黑体
plt.axis([7.6,20.4, 0.05,7.5])#设定横纵坐标尺度
plt.title('弗兰克-赫兹实验')#标题头
plt.xlabel('Ugk                                               软件工程_罗浩楠')
plt.ylabel('I')
plt.plot(x_list,y_list,'b-.')
#在图形中增加带箭头的注解
plt.annotate(r'波峰(8,1.097578594)',xy=(8,1.097578594),xytext=(8,3),arrowprops=dict(facecolor='black',shrink=0.1,width=1))
plt.annotate(r'波峰(9.2,1.007738703)',xy=(9.2,1.007738703),xytext=(9.2,3.5),arrowprops=dict(facecolor='black',shrink=0.1,width=1))
plt.annotate(r'波峰(13.2,3.095992035)',xy=(13.2,3.095992035),xytext=(13.2,4),arrowprops=dict(facecolor='black',shrink=0.1,width=1))
plt.annotate(r'波峰(16.8,7.098148851)',xy=(16.8,7.098148851),xytext=(16.8,4.5),arrowprops=dict(facecolor='black',shrink=0.1,width=1))
plt.annotate(r'波峰(17.6,7.031179256)',xy=(17.6,7.031179256),xytext=(17.6,5),arrowprops=dict(facecolor='black',shrink=0.1,width=1))
plt.annotate(r'波峰(20.2,5.09826933)',xy=(20.2,5.09826933),xytext=(20.2,6),arrowprops=dict(facecolor='black',shrink=0.1,width=1))
plt.savefig(r'D:\\a.PNG',dpi=600)#保存PNG图片
plt.grid(True)#网格显示
plt.show()
