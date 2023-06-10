# Como contribuir?
Esta obra tem a [licença Creative Commons "Atribuição" 4.0 Internacional][cc-by], e é um material educacional livre, aceita contribuições via pull requests no GitHub. Este documento tem a responsabilidade de alinhar as contribuições de acordo com os padrões estabelecidos no mesmo. Em caso de dúvidas, [abra uma issue](https://github.com/ViictorWebTech/livecoding-brazil/issues/new).


### Fork

Primeiramenta faça um [Fork ou Bifurcação](https://docs.github.com/pt/get-started/quickstart/contributing-to-projects), do repositório, que funcionará como um cópia do repositório para sua conta.

Clique no **Fork**

![](https://docs.github.com/assets/cb-23088/mw-1000/images/help/repository/fork_button.webp)

Siga as etapas para fazer a cópia do repositório em sua conta.

### Faça o Clone

Após o fork ser feito, o repositório irá aparecer na sua conta, abra o repositório e clique no botão Code

![](https://docs.github.com/assets/cb-20363/mw-1000/images/help/repository/code-button.webp)

Irá aparecer três opções para clonar, selecione a que deseja e copie o comando

Por exemplo
```
git clone https://github.com/NOME_SEU_USUARIO/livecoding-brazil.git
```

Onde o **NOME_SEU_USUARIO** é seu usuário do github.


Após concluido acesse o diretório a abra o repositório com o seu editor favorito, nesse caso estou usando o vscode
```
cd livecoding-brazil
code .
```

Faça o checkout para uma nova branch para você trabalhar na edição que precisa,você pode seguir os [Padrões e nomeclaturas do git](https://www.brunodulcetti.com/padroes-e-nomenclaturas-no-git/)
```
git checkout -b nome_da_branch
```

Faça suas alterações e confirme-as
```
git commit -m '<mensagem_commit>'
```

Envie para o branch original
```
git push origin nome_da_branch
```

Envie um Pull Request para esse repositório

- Adicione um título e uma descrição que deixe claro sua sugestão :)

**Depois que seu pull request for mergeado**

> Depois que seu pull request for mergeado, você pode apagar sua branch. 

## Resumo
1. Fork este repositório.
2. Envie seus commits em português.
3. Solicite a pull request.
4. Insira um pequeno resumo das alterações.

## Recomendações (Opcional)
**Para uma melhor semântica nos commits, recomendo o repositório de [Yuri Code](https://github.com/iuricode/) sobre [COMMITS SEMÂNTICOS](https://github.com/iuricode/padroes-de-commits). Assim ficará mais fácil para avaliar seu pull request.**

**Assista esse vídeo caso queira aprender mais sobre contribuições.**

- [COMO CONTRIBUIR COM OPEN SOURCE NO GITHUB - DANIEL BONIFACIO](https://www.youtube.com/watch?v=n0lSrPl9DTc)

[cc-by]: https://creativecommons.org/licenses/by/4.0/deed.pt_BR
