阅读一些在线小说或者漫画  
1.看漫画用eimg_reader.py, 看小说用ebook_reader.py  
2.配置文件和书签在conf文件夹里面  
3.解析不可能做到覆盖所有网站，但是除了有特别复杂的js的网站外，理论上都可以调整之后正常支持  
4.此项目使用了beautifulsoup4,但是pythonista自带库比老旧，用https://github.com/ywangd/stash 。在安装用`pip install module_name`安装之后，用`del sys.modules['module_name']`来移除原有依赖，之后pythonista会自动切换到新安装的包上,可以用`module_name.__file__`测试是否正常移除了依赖。
