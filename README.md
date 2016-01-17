# sphinx-latex-table-test

Note: this bug has been fixed in Sphinx 1.3.1, and TeX Live 2015 pair.

An example of how multirow+multicolumn table fails on building LaTeX document on Sphinx.

For Sphinx 1.2.2, and TeX Live 2014.

See `source/index.rst` for the example.

See `build/latex/sphinx-latex-table-test.log` for the compilation log.

## References

* <http://docutils.sourceforge.net/docs/user/latex.html#tables> (see Section 7.2.2)
* <http://sourceforge.net/p/docutils/code/HEAD/tree/trunk/docutils/docutils/writers/latex2e/__init__.py#l1977>
* <http://tex.stackexchange.com/questions/87714/multirow-nested-table>
* 日本語での解説 (details in Japanese): <http://www.python.jp/pipermail/sphinx-users/2014-August/001018.html>

