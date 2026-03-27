 # MISSÃO AURORA SINGER -  Descrição do projeto
 
   A MISSÃO AURORA SINGER é um projeto em PYTHON que simula o projeto de checagem e autorização que regula o lançamento de um foguete. O sistema executa uma serie de 
 verificações pré-decolagem, gera telemetria simulada (temperaturas, energia, pressão, integridade e status de módulos) utilizando valores aleatórios, que são apresentadoS em tabelas com Pandas, para facilitar a leitura.
	 
   Além da telemetria, o projeto faz uma análise energética estimando a capacidade total,  carga atual, perdas, energia disponível, consumo na decolagem e autonomia. 
 Sendo assim, é definido um status de energia (Ok ou crítico).
 
   Em fim, este projeto utiliza auxílio da Inteligência Artificial (IA) com Scikit – Learn, treinada com um conjunto de dados, para prever se é seguro ou não o lançamento do foguete. A decisão final só autoriza a decolagem, quando a previsão da IA indica lançamento permitido e a análise energética retorna energia suficiente; 
 caso contrário, o lançamento é negado.

   Tecnologias e bibliotecas usadas (árvore de decisão).  Saída do sistema de telemetria em tabela, relatório de energia e mensagem final de autorização ou cancelamento do lançamento.
