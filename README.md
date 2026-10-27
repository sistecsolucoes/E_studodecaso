# Painel de consumo e compensação solar

Painel HTML com 19 unidades, gráficos de consumo, filtros, detalhes por unidade e simulação de autoconsumo para instalações individuais.

## Arquivos

- index.html: painel completo com CSS, JavaScript e dados incorporados. Não precisa de pasta assets ou instalação de programas.
- .nojekyll: permite servir os arquivos estáticos sem processamento Jekyll.
- README.md: instruções de publicação.

## Publicar pelo navegador

1. Crie um repositório no GitHub. Para GitHub Free, use um repositório público para publicar com Pages.
2. Extraia este ZIP no computador.
3. No repositório, selecione Add file > Upload files.
4. Envie index.html, README.md e .nojekyll para a raiz do repositório, sem uma pasta intermediária. Se o arquivo .nojekyll estiver oculto no computador, index.html e README.md são suficientes para este painel.
5. Confirme em Commit changes.
6. Abra Settings > Pages.
7. Em Source, escolha Deploy from a branch.
8. Escolha a branch main e a pasta /(root). Clique Save.
9. Aguarde a publicação. O endereço aparecerá em Settings > Pages, normalmente https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/.

Não envie apenas o arquivo ZIP: extraia e envie seu conteúdo. O arquivo index.html deve estar diretamente na raiz.

## Atualizar

Substitua index.html e confirme o commit. O Pages republica a versão atualizada.

## Uso

- Clique nas categorias para filtrar a situação solar.
- Busque unidades e filtre pela distribuidora.
- Clique nas barras ou linhas para consultar detalhes.
- Na simulação, altere o consumo direto geral ou os percentuais e volumes por unidade.
- Use Imprimir / salvar PDF para exportar a visualização pelo navegador.
- As alterações da simulação valem durante a sessão e não alteram os dados originais ou o arquivo no GitHub.

## Dados e hipóteses

Os 19 documentos possuem referências entre julho e setembro de 2026. A soma reúne ciclos distintos e não um mês sincronizado. A simulação usa cada consumo da rede como referência mensal, com 80% de autoconsumo como hipótese inicial editável e encargo de R$ 0,28/kWh. Não é medição do perfil horário, orçamento ou economia adicional garantida sobre os contratos atuais. Para locais com geração existente, o consumo da rede não inclui o autoconsumo já realizado.

## Acesso

Este painel é estático, contém valores de consumo e faturamento das unidades e não possui login. Na publicação padrão do GitHub Pages, a página fica acessível pela internet. Um repositório privado não torna automaticamente o site privado.

Documentação: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
