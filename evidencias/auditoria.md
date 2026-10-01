# Resultado da auditoria

Auditoria feita em nova conversa, separada da consulta, com docs/prompts/auditoria.md.

## Achado 1 - CRÍTICO
Afirmação: "a consumidora tem 90 dias para reclamar (art. 26 do CDC)".
Evidência: resposta_inicial.md, item 2. O art. 26 não está em apoio/.
Motivo: afirmação fora das fontes delimitadas, contrariando a especificação.
Correção sugerida: retirar a afirmação e declarar que o prazo para reclamar não pode ser respondido com as fontes atuais.

## Achado 2 - ALERTA
Afirmação: "a geladeira é produto essencial e a consumidora poderia ter exigido essas alternativas de imediato".
Evidência: resposta_inicial.md, item 1 / fonte_2.md, § 3º.
Motivo: o § 3º menciona "produto essencial", mas nenhuma fonte do projeto define quais produtos são essenciais. A conclusão é uma extrapolação.
Correção sugerida: apresentar o § 3º como hipótese a ser analisada, sem afirmar que a geladeira é essencial.

## Achado 3 - ALERTA
Afirmação: "pode escolher entre substituição, restituição ou abatimento".
Evidência: resposta_inicial.md, item 1 / fonte_2.md, § 1º.
Motivo: o texto está correto, mas a resposta não declara que depende da confirmação das datas e de que não houve acordo de prazo diferente (§ 2º).
Correção sugerida: declarar o limite da orientação e condicionar à conferência dos documentos.

## Achado 4 - ALERTA
Afirmação: menção a "medicamento que precisa de refrigeração" no caso sanitizado.
Evidência: caso_sanitizado.md, "Outras informações" / limites_e_sigilo.md.
Motivo: é informação de saúde. Está genérica e sem identificar quem usa, mas exige cuidado.
Correção sugerida: manter genérica e não repetir na orientação final.

## Achado 5 - OK
Responsabilidade solidária da loja sustentada pelo art. 18, caput (fonte_2.md).

## Achado 6 - OK
Não foram encontrados nome, CPF, endereço, número de pedido, protocolo ou marca na resposta inicial.