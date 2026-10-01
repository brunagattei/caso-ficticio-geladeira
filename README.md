# Horizonte Consumidor - caso fictício

Atividade preparatória para a N1 da disciplina Inteligência Artificial Jurídica (Prof. Edson Vaz Lopes).
Aluna: Bruna Gattei Micheletti.

## Problema
Geladeira nova com defeito, retirada pela assistência técnica e não devolvida em mais de 30 dias. A consumidora pede uma orientação inicial sobre substituição ou reembolso, prazo e responsabilidade da loja.

## Como navegar
- entrada/ preserva o relato original (nunca vai para a IA);
- apoio/ contém o caso sanitizado e as únicas fontes permitidas na consulta;
- docs/ define as regras, a especificação e os prompts;
- evidencias/ registra a resposta da IA, a verificação, a auditoria e a revisão humana;
- entrega/ contém a orientação final.

## Ordem do fluxo
1. docs/limites_e_sigilo.md
2. apoio/caso_sanitizado.md, apoio/fonte_1.md (nota fiscal), apoio/fonte_2.md (CDC, art. 18)
3. docs/especificacao.md
4. docs/prompts/consulta_rag.md → evidencias/resposta_inicial.md
5. evidencias/verificacao.md
6. docs/prompts/auditoria.md (em nova conversa) → evidencias/auditoria.md
7. evidencias/revisao_humana.md
8. entrega/orientacao_inicial.md

## Repositório
https://github.com/brunagattei/caso-ficticio-geladeira.git

## Como executar
Ler docs/prompts/consulta_rag.md e enviar para a IA somente os arquivos de apoio/.