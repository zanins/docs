---
title: GitHub Desktop用のGitの設定方法
shortTitle: Configuring Git
intro: Gitをまだインストールしていない場合、GitHub Desktopを使う前にGitを設定する必要があります。
versions:
  free-pro-team: '*'
---

{{ site.data.variables.product.prodname_desktop }} uses the email address you set in your local Git configuration to connect commits with your account on {{ site.data.variables.product.product_name}}.

{{ site.data.reusables.desktop.update-email-address }}

{% tip %}

**Tip**: 公開コミットをした場合、Gitコンフィグレーションにあるメールアドレスは皆に表示されます。 詳詳細は「[コミットメールアドレスを設定する](/articles/setting-your-commit-email-address/)」を参照してください。

{% endtip %}

{% mac %}

{{ site.data.reusables.desktop.sign-in-choose-product }}
{{ site.data.reusables.user_settings.access_settings }}
{{ site.data.reusables.user_settings.emails }}
{{ site.data.reusables.desktop.copy-email-git-config }}
{{ site.data.reusables.desktop.return-to-desktop }}
{{ site.data.reusables.desktop.mac-select-desktop-menu }}
7. In the Preferences window, click **Git**. ![[Preferences] メニュー内の Git ペイン](/assets/images/help/desktop/mac-select-git-pane.png)
{{ site.data.reusables.desktop.name-field-git-config }}
  ![Git コンフィグレーション内の [Name] フィールド](/assets/images/help/desktop/mac-name-git-config.png)
{{ site.data.reusables.desktop.paste-email-git-config }}
  ![Gitコンフィグレーションフィールドに貼り付けられたEメールアドレス](/assets/images/help/desktop/mac-email-git-config.png)
{{ site.data.reusables.desktop.click-save-git-config }}
  ![Save button in Git configuration field](/assets/images/help/desktop/mac-save-git-config.png)

{% endmac %}

{% windows %}

{{ site.data.reusables.desktop.sign-in-choose-product }}
{{ site.data.reusables.user_settings.access_settings }}
{{ site.data.reusables.user_settings.emails }}
{{ site.data.reusables.desktop.copy-email-git-config }}
{{ site.data.reusables.desktop.return-to-desktop }}
{{ site.data.reusables.desktop.windows-choose-options }}
8. In the Options window, click **Git**. ![[Options] メニュー内の Git ペイン](/assets/images/help/desktop/windows-select-git-pane.png)
{{ site.data.reusables.desktop.name-field-git-config }}
  ![Git コンフィグレーション内の [Name] フィールド](/assets/images/help/desktop/windows-name-git-config.png)
{{ site.data.reusables.desktop.paste-email-git-config }}
  ![Gitコンフィグレーションフィールドに貼り付けられたEメールアドレス](/assets/images/help/desktop/windows-email-git-config.png)
{{ site.data.reusables.desktop.click-save-git-config }}
  ![Save button in Git configuration field](/assets/images/help/desktop/windows-save-git-config.png)

{% endwindows %}

### 参考リンク

- "[GitHubアカウントへのEメールアドレスの追加](/articles/adding-an-email-address-to-your-github-account/)"
- [コミットメールアドレスを設定する](/articles/setting-your-commit-email-address/)