# E办公文档的隐藏威胁 - GeekCon 2023



This is our slides for GeekCon 2023


OLE，全称叫做对象链接和嵌入，这个机制是用来支持用户在文档中编辑由其他应用程序生成的对象。Microsoft Office为此提供了一个支持接口，使得在文档中嵌入如声音片段、电子表格和位图等OLE对象变得轻而易举。

在Win11和Windows Server 2022中，我们发现了两个与OLE紧密相关的安全漏洞。在Microsoft Office环境中，这些漏洞可以被恶意触发，从而为攻击者提供了一个可利用的入侵通道。

这两个漏洞容易利用，但是容易被终端用户注意到。为了提高攻击的隐蔽性和成功率，我们进行了深入的技术研究，并采用了一系列策略来优化和完善其触发和利用机制。

在本次演讲中，我们将详细探讨并现场演示如何更加高效、隐蔽地利用这类漏洞，并提出对应的防御方案。