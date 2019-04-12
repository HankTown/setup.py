📦 setup.py (适用于人类)
=======================

此存储库提供了[一个示例setup.py] file, that can be used
文件，可用于引导您的下一个Python项目。它包括一些先进的模式和最佳实践setup.py，以及一些评论出来的好东西。
例如，这setup.py提供了一个$ python setup.py upload 命令，它创建一个通用轮（和sdist）并使用[Twine]上传到[PyPi] , 而不需要烦人的 文件。它还会自动创建/上传新的git标签。setup.cfg
简而言之，setup.py文件可能是令人生畏的，当第一次开始时 - 甚至Guido已经听说过，“每个人都有货币崇拜主义”。这是真的 - 所以，我希望这个repo是从:)复制粘贴的最佳位置
如果您有兴趣在财务上支持Kenneth Reitz开源，请考虑[访问此链接](https://cash.me/$KennethReitz).您的支持极大地促进了动机的可持续性，因为开源不再是我日常工作的一部分。

[看看这个例子][一个示例setup.py]

![image]

要做的
-----

-   测试通过$ setup.py test（如果它简洁）。
鼓励pull request！


更多资源
--------------

-   [什么是setup.py？] 在Stack Overflow上
-   [官方Python包装用户指南](https://packaging.python.org)
-   [Hitchhiker的包装指南]
-   [Python包的Cookiecutter模板]

执照
-------

这是免费且无阻碍的软件发布到公共领域。
任何人都可以出于任何目的，商业或非商业，以任何方式，以源代码形式或编译二进制文本自由复制，修改，发布，使用，编译，销售或分发此软件。
✨🍰✨


  [一个示例setup.py]: https://github.com/kennethreitz/setup.py/blob/master/setup.py
  [PyPi]: https://docs.python.org/3/distutils/packageindex.html
  [Twine]: https://pypi.python.org/pypi/twine
  [image]: https://farm1.staticflickr.com/628/33173824932_58add34581_k_d.jpg
  [什么是setup.py？]: https://stackoverflow.com/questions/1471994/what-is-setup-py
  [Hitchhiker的包装指南]: https://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/creation.html
  [Python包的Cookiecutter模板]: https://github.com/audreyr/cookiecutter-pypackage
