A aplicação SaudeIntegrada visa realizar a centralização de dados externas ao ecossitema do SUS, de forma a melhorar os indicadores. Para tal foram usados as seguintes tecnologias, sendo requisitos de sistemas são as mesmas ferramentas citadas a baixo:

 - Java, versão 21
Optamos pela eficiência e suporte a virtual threads, garantindo melhor desempenho em operações concorrentes e maior longevidade da aplicação.

 - Maven, versão 3.9.9
Facilita a automação de builds e o gerenciamento de dependências, otimizando o ciclo de desenvolvimento.

 - Framework Quarkus, versão 3.15
O uso no backend foi motivado pelo seu alto desempenho, inicialização rápida, baixo consumo de memória e suporte à compilação nativa com GraalVM, ideal para aplicações escaláveis na nuvem. Ele facilita a construção de APIs REST e aproveita o ecossistema Java consolidado.

 - Framework Angular, versão 17.3.12
Enquanto o Angular no front permite a modularização, excelente integração com APIs, suporte a PWA e ferramentas nativas para criação de interfaces dinâmicas e escaláveis. Ambos garantem alta performance, fácil manutenção e uma experiência consistente ao usuário.

 - Node 20.11
Complementa o ambiente, fornecendo uma base sólida para a execução de scripts e gerenciamento de pacotes, agilizando o desenvolvimento e build da aplicação​.

	Essas versões estáveis e maduras garantem previsibilidade e minimizam riscos, sendo ideais para manter um ciclo de vida sustentável e seguro em produção.

COMANDOS PARA EXECUTAR O CÓDIGO
 - angular "npm install" (instala as bibliotecas)
 - angular "ng serve" (inicia servidor de local)
 - quarkus "./mvnw compile quarkus:dev" (inicia código)

