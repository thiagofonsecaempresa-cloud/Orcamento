# São Hostel — Gerador de Orçamentos

Aplicativo estático para GitHub Pages. Não precisa de backend nem de bibliotecas externas.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (por exemplo, `sao-hostel-orcamentos`).
2. Envie `index.html` e este `README.md` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/(root)` e salve.
6. Aguarde a publicação e abra o endereço mostrado na área Pages.

## Gerar o PDF

Clique em **Gerar / salvar PDF**. O aplicativo monta a proposta e chama a impressão nativa do navegador (`window.print()`), sem depender de bibliotecas de PDF externas. No computador, escolha **Salvar como PDF**. Em dispositivos móveis, use a opção de imprimir/salvar/compartilhar oferecida pelo navegador e pelo sistema.

## Observações

- O cálculo e a montagem do documento são feitos no navegador.
- O formulário não envia dados a um servidor nem grava automaticamente dados de clientes.
- Unidade selecionável: Mairinque ou São Roque.\n- Informa disponibilidade de suítes triplas/duplas, sugere combinações e permite aplicar uma combinação ao orçamento.
- Tarifas iniciais são exemplos editáveis. Confira os valores e as condições antes de enviar uma proposta.
- A estimativa de quartos usa a capacidade máxima (triplo: 3 pessoas; duplo: 2 pessoas). A disponibilidade real precisa ser confirmada.
