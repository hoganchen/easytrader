打包wheel

1. 编辑setup.py，修改版本信息

2. 编辑easytrader/__init__.py，修改版本信息

3. 打包wheel
python setup.py bdist_wheel
打包好的.whl文件位于dist目录下