O Readme desse repositório representará o primeiro desafio de projeto realizado no curso.

Relatório de Implementação de Serviços AWS

📅 Data: 01/04/2025

🏢 Empresa Fictícia: Abstergo Industries

👤 Responsável: Pedro Vieira

Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Pedro Vieira. O objetivo do projeto foi reduzir custos operacionais de forma imediata utilizando três serviços estratégicos da AWS.

Descrição do Projeto
Construído em três etapas, cada uma focada em uma solução específica para otimizar o armazenamento, processamento e automação de dados.

Etapa 1: Amazon S3 + Intelligent Tiering
🔹 Foco da ferramenta: Armazenamento otimizado e econômico para dados farmacêuticos.

📌 Descrição do caso de uso:
A empresa farmacêutica precisa armazenar grandes volumes de dados, como históricos de vendas, catálogos de medicamentos e registros de clientes. O Amazon S3 foi escolhido por sua escalabilidade e confiabilidade, e a ativação do Intelligent Tiering reduz custos ao mover automaticamente os dados para camadas de armazenamento mais baratas com base na frequência de acesso.

✅ Benefício: Redução de custos de armazenamento sem impacto no desempenho, garantindo que os dados menos acessados sejam armazenados de maneira mais econômica sem a necessidade de intervenção manual.


Etapa 2: Amazon Aurora (RDS)
🔹 Foco da ferramenta: Banco de dados relacional de alta performance e escalabilidade.

📌 Descrição do caso de uso:
Embora o S3 seja eficiente para armazenar dados não estruturados, a empresa precisa de um banco de dados transacional para gerenciar estoques, pedidos, dados de clientes e interações de produtos. O Amazon Aurora foi escolhido por sua alta escalabilidade, performance otimizada e redução de custos operacionais em comparação com bancos de dados tradicionais.

✅ Benefício: O Aurora se integra perfeitamente com o S3, permitindo um fluxo contínuo de dados. Além disso, sua arquitetura otimizada reduz a necessidade de gerenciamento manual, garantindo alta disponibilidade e baixo custo sem comprometer a eficiência.


Etapa 3: AWS Lambda
🔹 Foco da ferramenta: Automação e processamento de dados em tempo real sem necessidade de servidores.

📌 Descrição do caso de uso:
Com S3 e Aurora implementados, a empresa precisa de um serviço que automatize processos como processamento de registros médicos, notificações automáticas e movimentação de dados entre S3 e Aurora. O AWS Lambda permite que essas tarefas sejam executadas sob demanda, sem necessidade de provisionar servidores.

✅ Benefício: Redução de custos operacionais, pois o Lambda cobra apenas pelo tempo de execução, eliminando a necessidade de manter instâncias rodando continuamente. Além disso, ele melhora a eficiência ao integrar os sistemas de armazenamento e banco de dados da empresa de forma automatizada.

Conclusão
A implementação dessas três ferramentas da AWS na Abstergo Industries resultará em uma redução significativa de custos e um aumento de eficiência operacional.

✔️ O S3 + Intelligent Tiering reduz os custos de armazenamento ao ajustar automaticamente os dados para camadas mais baratas com base no uso.

✔️ O Amazon Aurora fornece um banco de dados de alta performance e escalável, garantindo gestão eficiente das informações e redução de custos em comparação com bancos tradicionais.

✔️ O AWS Lambda automatiza processos críticos, reduzindo custos operacionais e eliminando a necessidade de servidores dedicados para processamento de dados.


🔎 Recomenda-se a continuidade da utilização dessas ferramentas, juntamente com monitoramento contínuo e a exploração de novas soluções AWS que possam aprimorar ainda mais os processos e otimizar custos ao longo do tempo.
