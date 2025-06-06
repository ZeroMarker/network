## 心脏出血漏洞
心脏出血漏洞（英语：Heartbleed bug），简称为心血漏洞，是一个出现在加密程序库OpenSSL的安全漏洞，该程序库广泛用于实现互联网的传输层安全（TLS）协议。它于2012年被引入OpenSSL，2014年4月首次向公众披露。使用存在缺陷的OpenSSL实例时，无论是服务器还是客户端，都可能因此而受到攻击。此问题的原因是在实现TLS的心跳扩展时没有对输入进行适当验证（缺少边界检查）[3]，因此漏洞的名称来源于“心跳”（heartbeat）[4]。该程序错误属于缓冲区过读[5]，即可以读取的数据比应该允许读取的还多[6]。

![Heartbleed](https://upload.wikimedia.org/wikipedia/commons/thumb/d/dc/Heartbleed.svg/330px-Heartbleed.svg.png)