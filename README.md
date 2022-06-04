これはCode for SAKEの公式Webサイト(またはそのリソース)です。

# github.io

https://code-for-sake.github.io/

# 開発環境
bootstrapをsassでカスタマイズできる環境として
GitHub Pagesをローカルでテストできる環境で作成しました。
https://docs.github.com/ja/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll



Jekyll 4.0 comes with some major changes, notably:

  * Our `link` tag now comes with the `relative_url` filter incorporated into it.
    You should no longer prepend `{{ site.baseurl }}` to `{% link foo.md %}`
    For further details: https://github.com/jekyll/jekyll/pull/6727

  * Our `post_url` tag now comes with the `relative_url` filter incorporated into it.
    You shouldn't prepend `{{ site.baseurl }}` to `{% post_url 2019-03-27-hello %}`
    For further details: https://github.com/jekyll/jekyll/pull/7589

  * Support for deprecated configuration options has been removed. We will no longer
    output a warning and gracefully assign their values to the newer counterparts
    internally.