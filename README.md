# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS | Abstergo Industries 

Data: 10/04/26   
Empresa: Abstergo Industries 
Responsável: Júlio César 

## 💊 Projeto: Farmácia Cloud-Native – Otimização e Redução de Custos

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Júlio César . O objetivo do projeto foi elencar serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
📝 Descrição do Projeto
Este projeto propõe a modernização da infraestrutura tecnológica de uma unidade farmacêutica utilizando os serviços da Amazon Web Services (AWS). O foco principal é a transição de um modelo de custos fixos (CapEx) com servidores locais para um modelo de custos variáveis (OpEx), focado em eficiência operacional, automação de processos e redução drástica de desperdícios de estoque.

🎯 Objetivos
Minimizar Custos: Eliminar gastos com manutenção de hardware local e energia.

Otimizar Processos: Automatizar a leitura de documentos e o gerenciamento de estoque.

Escalabilidade: Garantir que o sistema suporte picos de demanda (ex: datas promocionais) sem travamentos.

## Etapa 1: 
- Amazon RDS (Relational Database Service)
- O RDS cuida de tarefas complexas como backups automáticos, patches de segurança e alta disponibilidade.

Otimização de Custos: * Elimina a necessidade de um servidor físico e nobreaks.

Uso de instâncias Reserved para reduzir em até 72% os custos de computação em contratos de longo prazo.

- Implementação: Migração do banco de dados local (MySQL/PostgreSQL) para uma instância gerenciada na nuvem.

## Etapa 2: 
- Amazon Textract
- Implementação: Integração de scanners e tablets no balcão para leitura automática de receitas médicas e notas fiscais de fornecedores.

Explicação do Serviço: Ferramenta de Machine Learning que extrai dados e textos de documentos digitalizados com precisão superior ao OCR tradicional.

Otimização de Custos:

Redução de horas-homem gastas em digitação manual.

Prevenção de erros operacionais que geram glosas (não pagamentos) de convênios médicos.

## Etapa 3: 
- Amazon SNS (Simple Notification Service)
- Implementação: Configuração de gatilhos (triggers) baseados nas datas de vencimento dos lotes de medicamentos.

Explicação do Serviço: Serviço de mensagens push, SMS e e-mail para comunicação em massa ou direcionada.

- Otimização de Custos:

Minimização de Perdas: Alertas automáticos 30/60 dias antes do vencimento permitem ações de "queima de estoque".

Fidelização: Avisos automáticos aos clientes sobre a necessidade de renovar medicamentos de uso contínuo, garantindo a receita mensal.

## 📑 Considerações Finais
O presente projeto demonstrou que a adoção de soluções de computação em nuvem é um diferencial competitivo essencial para o setor farmacêutico. A utilização do Amazon RDS garantiu a integridade e alta disponibilidade dos dados críticos; o Amazon Textract revolucionou a entrada de dados através da automação inteligente; e o Amazon SNS proporcionou um controle proativo de perdas e uma comunicação eficiente com o cliente.

Em suma, a transição para o modelo de nuvem da AWS não representa apenas uma modernização tecnológica, mas uma estratégia de otimização de custos operacionais (OpEx). A automação reduz o erro humano e libera a equipe para atividades de maior valor, enquanto a elasticidade da nuvem garante que a farmácia pague apenas pelo que utiliza, tornando o projeto viável e altamente escalável.

## Conclusão
A Abstergo Industries tem como esperado a implementação dos serviços Amazon RDS, Textract e SNS criando um ecossistema digital que ataca as três maiores dores de uma farmácia: a fragilidade da infraestrutura física, a lentidão operacional e o desperdício de estoque.

Ao migrar para a nuvem AWS, a farmácia deixa de investir em hardware depreciável e passa a investir em escalabilidade e inteligência. O resultado final é uma operação mais enxuta, com custos reduzidos e uma experiência de atendimento superior, garantindo a sustentabilidade financeira do negócio a longo prazo.

## Anexos

### 📚 Referências e Documentação

* [Amazon RDS - Banco de Dados Gerenciado](https://aws.amazon.com/pt/rds/)
* [Amazon Textract - Extração Inteligente de Documentos](https://aws.amazon.com/pt/textract/)
* [Amazon SNS - Serviço de Mensageria e Notificações](https://aws.amazon.com/pt/sns/)

Assinatura do ResponsÃ¡vel pelo Projeto:

Júlio César Pereira de Freitas Filho 


Este projeto é fictício e foi desenvolvido para fins educacionais.

 ![alt text](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExNDAwaWFyZnp0dDhnMWRodXBocHd5NzR2cTJkN2szaGI1dDBlNjJnMCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/Ze3KkbwQ74xuDpfeYG/giphy.gif)





