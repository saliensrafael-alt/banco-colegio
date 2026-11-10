# Banco Imobiliário da Turma

Jogo de sala de aula: saldo, transferências, compra e venda de propriedades
(10 empresas, 10 parques e 5 bancos) e validação do administrador.

## Como funciona o armazenamento
Não usa banco de dados externo. Tudo é JavaScript puro e os dados ficam no
`localStorage` do navegador.

- Funciona no GitHub Pages (site estático).
- Todos devem usar o MESMO computador e navegador. Abas diferentes se
  sincronizam sozinhas (ex.: uma aba do administrador e outra do aluno).
- Celulares ou computadores diferentes NÃO compartilham dados.
- Use "Exportar backup" na tela do administrador. Limpar os dados do
  navegador apaga o jogo.

## Publicar
1. Crie um repositório e envie `index.html` e `README.md`.
2. Settings > Pages > branch `main`, pasta `/ (root)`.

## Primeiro uso
1. Aba Administrador: crie a senha master e clique em "Criar as 25 propriedades".
2. Alunos se cadastram na aba Jogador (começam com R$ 1.000).
