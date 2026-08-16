Projeto acadêmico elaborado em conjunto com colegas de classe como requisito parcial para obtenção de nota.



Meu papel no projeto: Desenvolvimente parcial de diagramas UML, organizar e estruturar documentos, compilar ideias do grupo e redigir a documentação técnica oficial.







O Sistema OTMZ é um sistema de mobilidade urbana inteligente focado na redução do tempo de espera em cruzamentos, priorização de veículos de emergência e aumento da segurança de pedestres na Grande São Paulo. O projeto utiliza IA, IoT e análise de dados em tempo real para adaptar o tempo semafórico de forma ética e eficiente.  





Funcionalidades do MVP:


* Adaptação Semafórica em Tempo Real: Ajuste dinâmico dos tempos de sinal verde/vermelho com base no volume de veículos e pedestres.  



* Priorização de Emergências: Detecção de ambulâncias, bombeiros e polícia via GPS, rádio e sensores acústicos para abertura de rotas.  



* Acessibilidade Universal: Identificação de intenção de travessia e extensão do tempo de sinal para idosos e pessoas com mobilidade reduzida.  



* Central de Comando (Dashboard): Painel para operadores monitorarem filas, métricas de espera e alertas operacionais.  





Arquitetura em Camadas:



\[ Camada 1: Coleta ] ──> Sensores IoT, GPS, Rádio e Sensores Acústicos

&#x20;                                       │

\[ Camada 2: Processamento ] ──> Análise em tempo real + Motor de Regras e IA

&#x20;                                       │

\[ Camada 3: Decisão ] ──> Ajuste de fase semafórica e rotas prioritárias

&#x20;                                       │

\[ Camada 4: Supervisão ] ──> Central de Comando (Painel de Monitoramento)





Stack Tecnológica:



* IA \& Data Processing: Python  



* IoT \& Embedded: C / C++ (Integração com sensores e controladores)  



* Dashboard / Central: TypeScript  



* Banco de Dados: SQL (Métricas, alertas e histórico de eventos)

