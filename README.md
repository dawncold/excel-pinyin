# 为excel中添加pinyin列

```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt

python main.py <EXCEL_PATH>
```

## excel文件要求

* 只有一个sheet页
* 姓名在第二列，运行后会在第三列添加拼音，会保存新文件不破坏原文件
