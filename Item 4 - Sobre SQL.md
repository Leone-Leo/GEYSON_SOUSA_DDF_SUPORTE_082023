Segue a Query SQL utilizada em uma das perguntas do item 4 (as demais estão na metabase em: https://metabase-treinamentos.dadosfera.ai/collection/191-geyson-sousa-082023):

SELECT "PUBLIC"."TB__8Y3C3Y__EMPLOYEE"."JOBROLE" AS "JOBROLE", COUNT(*) AS "count"
FROM "DADOSFERA_PRD_TREINAMENTOS"."PUBLIC"."TB__8Y3C3Y__EMPLOYEE"
GROUP BY "PUBLIC"."TB__8Y3C3Y__EMPLOYEE"."JOBROLE"
ORDER BY "PUBLIC"."TB__8Y3C3Y__EMPLOYEE"."JOBROLE" ASC

Segue o print da visualização gerada: https://drive.google.com/file/d/1vLbJajSQxiXoSSE4tH5w_t46YebnRXiY/view?usp=sharing
Segue o print da visualização em gráfico de pizza: https://drive.google.com/file/d/1mkbKes8qV6Gty8UAhDd3QnNaO9Q_qvp8/view?usp=sharing 

O item bônus encontra-se em: https://metabase-treinamentos.dadosfera.ai/dashboard/39-dashboard-completo.
