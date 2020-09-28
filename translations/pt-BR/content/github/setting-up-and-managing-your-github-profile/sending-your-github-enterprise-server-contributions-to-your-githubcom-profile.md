---
title: Enviar as contribuições do GitHub Enterprise Server para o perfil do GitHub.com
intro: 'Você pode destacar seu trabalho no {{ site.data.variables.product.prodname_ghe_server }} enviando as contagens de contribuição para seu perfil do {{ site.data.variables.product.prodname_dotcom_the_website }}.'
redirect_from:
  - /articles/sending-your-github-enterprise-contributions-to-your-github-com-profile/
  - /articles/sending-your-github-enterprise-server-contributions-to-your-github-com-profile
  - /articles/sending-your-github-enterprise-server-contributions-to-your-githubcom-profile
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

{% note %}

**Notas:**
- A conexão entre as contas é controlada pela <a href="/articles/github-privacy-statement/" class="dotcom-only">Declaração de privacidade do GitHub</a>, e os usuários que ativam a conexão concordam com os <a href="/articles/github-terms-of-service/" class="dotcom-only">Termos de serviço do GitHub</a>.

- Antes de conectar seu perfil do {{ site.data.variables.product.prodname_ghe_server }} ao perfil do {{ site.data.variables.product.prodname_dotcom_the_website }}, um administrador do site deve habilitar o {{ site.data.variables.product.prodname_github_connect }} e habilitar o compartilhamento de contribuições entre os ambientes. Para obter mais informações, entre em contato com o administrador do seu site do {{ site.data.variables.product.prodname_ghe_server }}.

{% endnote %}

O perfil do {{ site.data.variables.product.prodname_dotcom_the_website }} mostra as contagens de contribuição do {{ site.data.variables.product.prodname_ghe_server }} dos últimos 90 dias. {{ site.data.reusables.github-connect.sync-frequency }} As contagens de contribuição do {{ site.data.variables.product.prodname_ghe_server }} são consideradas contribuições privadas. Os detalhes do commit mostrarão apenas quais são as contagens de contribuição e que as contribuições foram feitas no {{ site.data.variables.product.prodname_ghe_server }}.

Se quiserem, os usuários finais do {{ site.data.variables.product.prodname_ghe_server }} e do {{ site.data.variables.product.prodname_dotcom_the_website }} podem divulgar publicamente suas contagens de contribuição privadas. Para obter mais informações, consulte "[Mostrar ou ocultar contribuições privadas no perfil](/articles/publicizing-or-hiding-your-private-contributions-on-your-profile/)".

Para obter mais informações sobre como as contribuições são calculadas, consulte "[Gerenciar gráficos de contribuição no perfil](/articles/managing-contribution-graphs-on-your-profile/)".

{{ site.data.reusables.github-connect.access-dotcom-and-enterprise }}
{{ site.data.reusables.github-connect.access-profile-settings }}
{{ site.data.reusables.github-connect.github-connect-tab-user-settings }}
{{ site.data.reusables.github-connect.connect-dotcom-and-enterprise }}
{{ site.data.reusables.github-connect.authorize-connection }}
6. Em "Contributions" (Contribuições), selecione **Send my contribution counts to {{ site.data.variables.product.prodname_dotcom_the_website }}** (Enviar minhas contagens de contribuição para o {{ site.data.variables.product.prodname_dotcom_the_website }}) e clique em **Update contributions** (Atualizar contribuições). ![Caixa de seleção Send contributions (Enviar contribuições) e botão update contributions (atualizar contribuições)](/assets/images/help/settings/send-and-update-contributions.png)