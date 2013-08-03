douban-client-demo
==================

1. 请到 [豆瓣开发者页面](http://developers.douban.com/) 注册一个 App, 其中 **回调地址** 为: `http://127.0.0.1:5000/callback`;  
2. 配置 app.py 中 `KEY、SECRET` (对应 App 中的 API Key, Secret);
3. 在第 1 步注册的 App 中 **测试用户** 加入自己的账号;
4. 执行 `pip install -r pip-req.txt`;
5. 执行 `python app.py` 并访问 `http://127.0.0.1:5000` 即可.
