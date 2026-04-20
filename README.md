# pesquisa-cx-vml

Régua de NPS em HTML para disparo via e-mail marketing na RD Station.

## Como funciona

O arquivo `index.html` contém um bloco de tabela com 11 botões numerados de 0 a 10, cada um com uma cor correspondente à escala NPS (vermelho para notas baixas, verde para notas altas). Cada botão é um link independente que direciona o respondente para uma landing page específica da nota escolhida, hospedada na RD Station.

As URLs contêm parâmetros UTM para rastreamento. Quando o respondente preenche o formulário na landing page, a RD Station captura automaticamente os parâmetros e registra a nota no perfil do contato.

## Estrutura de rastreamento

- **utm_source:** rd-station
- **utm_medium:** email
- **utm_campaign:** nps-2026-04
- **utm_content:** nota-0 até nota-10 (identifica a nota escolhida)

## URLs por nota

| Nota | URL |
|------|-----|
| 0 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-0?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-0 |
| 1 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-1?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-1 |
| 2 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-2?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-2 |
| 3 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-3?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-3 |
| 4 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-4?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-4 |
| 5 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-5?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-5 |
| 6 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-6?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-6 |
| 7 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-7?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-7 |
| 8 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-8?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-8 |
| 9 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-9?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-9 |
| 10 | https://conteudo.vmlcomp.com.br/pesquisa-cx-nota-10?utm_source=rd-station&utm_medium=email&utm_campaign=nps-2026-04&utm_content=nota-10 |

## Como usar

Cole o conteúdo do `index.html` no bloco de HTML customizado do e-mail na RD Station. O bloco já está pronto para disparo, sem necessidade de alterações adicionais.

Para futuras campanhas, atualize o valor de `utm_campaign` em todos os links para refletir o novo período.

