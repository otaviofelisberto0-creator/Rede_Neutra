# RN 203 | Pagina Adm

Pagina auxiliar para o analista preparar os arquivos RSUL e Regional Leste.

## Fluxo

1. Escolher o CSV da RSUL.
2. Escolher o CSV da Regional Leste.
3. A pagina valida, filtra e consolida automaticamente.
4. Clicar em **Baixar CSV + JSON**.
5. Usar o botao **GitHub** para acessar o perfil de publicacao.
6. A pagina limpa os dados temporarios depois dos dois downloads.

## Filtros fixos

- `NM_GRUPO_OS = Instalacao`
- `NM_NOVO_DOMICILIO = Sim`
- `NM_MOTIVO_REAGENDA = 203 REDE EXTERNA COM PROBLEMA`
- `NM_TIPO_TRATAMENTO = COM QUEBRA DE AGENDA`
- `COD_NODE = GPONAVTAL`

## Arquivos gerados

- `RN-aa-mm.csv`: consolidado completo para supervisao.
- `RN-aa-mm.json`: consolidado agregado para o GitHub Release.

## GitHub

O botao GitHub abre: `https://github.com/otaviofelisberto0-creator`

## GitHub Pages

Envie `index.html`, `.nojekyll`, `README.md` e `RELEASE.md` para a raiz do repositorio. Em **Settings > Pages**, publique a branch principal pela pasta raiz.
