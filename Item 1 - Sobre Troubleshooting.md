Olá, tudo bem? Entendi que você está tendo problemas ao importar dados na Dadosfera por meio de uma pipeline de coleta. Analisando os logs, vejo que a pipeline foi executada, houve extração de dados da aba employee da planilha, mas não houve extração de dados nem catalogação nas outras abas da planilha. Confirme se os nomes das abas que você deseja importar estão corretos na configuração da pipeline, pois, de acordo com o log, as outras abas não estão sendo selecionada e, por isso, os dados não estão sendo importados. Vale lembrar que cada aba importada resultará em um dataset diferente no catálogo.
Isso pode indicar algumas possíveis questões.

Primeiramente, é preciso verificar a configuração da pipeline e garantir que tudo esteja configurado corretamente:

    Link da Planilha: Certifique-se de que o link da planilha esteja correto na configuração da pipeline. Ele deve ser a URL completa da planilha no Google Sheets.

    Permissões da Planilha: Verifique se a planilha possui as permissões corretas para ser acessada pela Dadosfera. Isso é crucial para que a plataforma possa extrair os dados.

    Formato dos Dados: Certifique-se de que os dados na planilha estejam formatados corretamente e não contenham erros que possam interferir na extração.

    Nomes das Colunas: Lembre-se de que, de acordo com a documentação da Dadosfera, as colunas não devem conter aspas duplas. Verifique se os nomes das colunas estão em conformidade.

Após verificar esses pontos, tente executar a pipeline novamente. Caso o problema persista, é recomendável verificar os logs detalhados para obter informações mais específicas sobre o erro.

Além disso, lembre-se de seguir as boas práticas ao carregar dados do Google Sheets para a plataforma, conforme mencionado na documentação da Dadosfera. Isso inclui garantir que a extensão do arquivo esteja correta (xlsx ou xls) e que os dados estejam devidamente formatados.

Estou aqui para ajudar no processo de resolução desse problema. Se precisar de mais assistência ou tiver alguma dúvida adicional, por favor, me informe. Vamos trabalhar juntos para solucionar essa questão e garantir que a importação dos dados seja bem-sucedida.