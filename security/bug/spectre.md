## 幽灵漏洞
幽灵（英语：Spectre）是一个存在于分支预测实现中的硬件缺陷及安全漏洞，含有预测执行功能的现代微处理器均受其影响[1][2]，漏洞利用是基于时间的旁路攻击，允许恶意进程获得其他程序在映射内存中的资料内容。[3][4][5]Spectre是一系列的漏洞，基于攻击行为类型，赋予了两个通用漏洞披露ID，分别是CVE-2017-5753（bounds check bypass，边界检查绕过）和CVE-2017-5715（branch target injection，分支目标注入），于2018年1月随同另一个也基于推测执行机制的、属于重量级信息安全漏洞的硬件缺陷“Meltdown”（熔毁）一同公布。由于该缺陷是推测执行机制导致的，加上不同处理器架构对推测执行又有不同的实现方式，因此这个缺陷无法获得根源上的修复而只能采取“见招拆招”式的方法防范，而且因机制所致，各种解决方案还有不可预料的性能下降。[6]

![Spectre](https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/Spectre_logo_with_text.svg/225px-Spectre_logo_with_text.svg.png)