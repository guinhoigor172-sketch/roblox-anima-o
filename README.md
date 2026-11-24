# Quita Score

Protótipo estático de uma simulação de quitação de dívidas.

## Correções aplicadas

- CPF limitado a 11 dígitos e formatado como `000.000.000-00`.
- Validação real dos dígitos verificadores do CPF.
- A etapa **Pagamento** aparece somente depois de informar nome e CPF válidos.
- Cartão limitado a 16 dígitos e exibido em grupos de quatro.

## Teste

- CPF: `529.982.247-25`
- Cartão: `4111 1111 1111 1111`
- O primeiro envio mostra `Erro 001`; fechar e tentar novamente conclui a simulação.

## Publicar no GitHub Pages

A branch `main` já deve estar configurada com `/ (root)` em **Settings → Pages**.

> Nenhuma cobrança é realizada e não há integração com banco neste protótipo.
