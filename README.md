# 💸 Racha do Rolê

**Divide a conta de qualquer rolê sem dor de cabeça.** Cada um leva ou paga uma coisa, e no fim o app calcula quem paga quem — no menor número de transferências possível.

> Cada um leva uma coisa. No fim, ninguém sai devendo pra ninguém.

## O problema que ele resolve

Churrasco, aniversário, viagem, happy hour: um trouxe a comida, outro a bebida, outro os extras, e ninguém sabe quanto precisa acertar com quem. O Racha do Rolê soma tudo, calcula a parte justa de cada um e mostra as transferências certinhas — normalmente 2 ou 3 no total, em vez de todo mundo se pagando.

## O que ele faz

- **Divisão por peso** — cada pessoa escolhe o quanto consome (de meia a 2 porções). Quem come/consome menos paga menos.
- **Bebida só pra quem bebe** — marque quem não bebe e essa pessoa fica de fora do rateio das bebidas.
- **Categorias** — comida, bebida e outros (extras, descartáveis, etc.) divididos de forma justa entre quem participa de cada um.
- **PIX pronto** — gera o código copia-e-cola e o QR Code já com o valor certo de cada transferência.
- **Manda no zap** — compartilha o resumo do acerto ou cobra cada pessoa direto pelo WhatsApp.
- **Salva o rolê** — guarda pra reabrir depois, e salva sozinho conforme você preenche.
- **Consolidado** — junta vários rolês num acerto final único, somando as pessoas pelo nome.

## Como a divisão funciona

1. Soma tudo que foi gasto.
2. Calcula a parte justa de cada pessoa: comida e extras por peso; bebida dividida igualmente entre quem bebe.
3. Compara com o que cada um já pagou: quem gastou mais tem a **receber**, quem gastou menos tem a **pagar**.
4. Casa o maior devedor com o maior credor até zerar, gerando o menor número de transferências.

## Como usar

1. Adicione **a galera** — nome, quanto cada um consome, se bebe, e a chave PIX de quem vai receber.
2. Lance **as compras** — quem pagou, o quê, quanto e a categoria.
3. Veja **o acerto** — os saldos e as transferências, com PIX, QR e botão de WhatsApp.
4. Precisa juntar mais de um evento? Use o **Consolidado**.

## Rodando

É um arquivo único (`index.html`), sem instalação. Abra no navegador do celular ou do computador — funciona até offline.

Publicado com **GitHub Pages**: `Settings → Pages → Deploy from a branch → main → / (root)`.

## Detalhes técnicos

- HTML, CSS e JavaScript puro, num arquivo só.
- Sem framework. Usa apenas Google Fonts e uma biblioteca de QR Code via CDN.
- O código PIX segue o padrão BR Code do Banco Central (com CRC16).
- Os dados salvos ficam **por aparelho/navegador** — não é uma sala compartilhada. Para várias pessoas editarem o mesmo rolê ao mesmo tempo, seria preciso um banco de dados por trás.

---

Feito pra dividir o rolê sem estresse. 🎉
