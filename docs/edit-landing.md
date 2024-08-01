---
title: Edit landing
author: 
updated: 2024/08/01
date: 2024/07/09
---

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

-   **版本控制**：使用 Git 作为版本控制系统，可追踪更改记录，还可以在需要时回滚版本，确保文档的质量和一致性。
-   **协作性强**：通过 pull request 和 issues，团队成员可以轻松地讨论、审查、修改和合并文档的更改。
-   **持续集成与部署**：支持自动化测试、构建和部署，贡献者 pull request 后可自动构建，实现预览，通过管理员审核后可自动构建整站。

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

