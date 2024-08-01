## 编辑前须知

首先，感谢您愿意为 **华师手册** 做出自己的贡献。

不过在开始之前，我们需要您了解 markdown 的基本语法，然后再参考 [如何参与](./intro/htc.md) 和 [格式手册](./intro/format.md) 里的内容，以避免在编辑时产生不必要的麻烦。
在阅读完之后，请点击下方的按钮，然后开始在 Github 上编辑。

<a id="btn-startedit" style="padding: 0.75em 1.25em; display: inline-block; line-height: 1; text-decoration: none; white-space: nowrap; cursor: pointer; border: 1px solid #6190e8; border-radius: 5px; background-color: #6190e8; color: #fff; outline: none; font-size: 0.75em;">开始编辑</a>


## 或者

如果您不太了解 markdown 语法，或者没有 Github 账号也没有关系，可以通过以下方式贡献。

1. 邮件提交

	发送邮件到 support@scnusw.online

2. 代理提交

	提交规范编写的 Word 图文给管理员，由管理员整理上传。

## 为什么要在 Github 上编辑

-   Github方便版本管理，清晰对比版本之间的区别，并能快速回滚。
-   强大的多人合作平台，多人提交以及多管理员审核。
-   成熟的自动化部署方案，通过审核后可自动构建整站。

<script>
	function getQueryVariable(name, dft)
	{
		var reg = new RegExp('(^|&)' + name + '=([^&]*)(&|$)', 'i');
		var r = window.location.search.substr(1).match(reg);
		if (r != null)
		{
			return unescape(r[2]);
		}
		return dft;
	}
	document.getElementById("btn-startedit").href = "https://github.com/SCNU-SW/SCNU-SW-Wiki/edit/main/docs" + getQueryVariable("ref", "");
</script>

