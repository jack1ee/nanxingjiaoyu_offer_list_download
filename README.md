# 获得南星offer录取结果小工具

功能：爬取南星教育录取案例界面所有offer的基本信息

亮点：

- 可以调整爬取offer的国家/地区，支持香港、新加坡、英国、美国、欧洲、中外合办的offer
- 可以调整爬取offer数量
- 最后生成excel表格，表格内容包括："学校","专业","GPA","语言","姓名","录取学校","录取专业","入学时间","4分换算gpa"

## 使用

1，安装python

2，安装python包

在本目录下打开终端

```
pip install -r requirements.txt
```

3，打开main.py

4，修改#config行下的内容

```python
#config
now_use_searchid = "uk" #选择要爬取的地区
pages =20 #选择要爬取的页数，一页16个
```

5，运行python

## 注意

1. 4分换算GPA不准，仅供参考，计算方式为：
   1. 设百分制gpa为a，4分制gpa为b, $$b=1.5+(a-60)/10$$
2. 部分内容为null，或者缺失，不影响使用，不影响程序运行
3. 所有内容仅供学习交流使用，获取内容均为互联网公开内容，本人不承担一切使用责任，请学习后立即删除

