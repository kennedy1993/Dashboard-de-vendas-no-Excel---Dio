# Dashboard-de-vendas-no-Excel---Dio

[README.md](https://github.com/user-attachments/files/23568506/README.md)
# Projeto: Dashboard Xbox Game Pass

## Descrição do Projeto
Este projeto tem como objetivo analisar dados de assinaturas do **Xbox Game Pass** e criar um **dashboard interativo** em Excel para responder perguntas de negócio relacionadas ao faturamento e vendas de planos e serviços adicionais.

## Dados Utilizados
Foram utilizados dois arquivos principais:

1. **base.xlsx.xlsx**
   - Contém os dados brutos das assinaturas, incluindo:
     - ID do assinante, nome, plano (Ultimate, Core, Standard)
     - Data de início, auto-renovação, preço da assinatura
     - Tipo de assinatura (Mensal, Trimestral, Anual)
     - Informações sobre EA Play Season Pass e Minecraft Season Pass
     - Valor total da assinatura considerando cupons e adicionais

2. **dashboard_xbox_finalizado.xlsx.xlsx**
   - Contém o dashboard final com:
     - Faturamento total de planos anuais
     - Faturamento separado por auto-renovação
     - Total de vendas do EA Play Season Pass
     - Total de vendas do Minecraft Season Pass
     - Visualizações e layout final do dashboard

## Perguntas de Negócio Respondidas
- Qual o faturamento total de vendas de planos anuais?
- Qual o faturamento total separado por auto-renovação?
- Qual o total de vendas do EA Play Season Pass?
- Qual o total de vendas do Minecraft Season Pass?

## Instruções para Reprodução
1. Certifique-se de ter o **Microsoft Excel** instalado.
2. Abra o arquivo `dashboard_xbox_finalizado.xlsx.xlsx` para visualizar o dashboard.
3. Caso queira gerar novamente os cálculos:
   - Abra o arquivo `base.xlsx.xlsx`.
   - Utilize **Tabelas Dinâmicas** no Excel para calcular os totais conforme as perguntas de negócio.
4. Para personalização:
   - Ajuste cores e layout conforme a paleta definida na aba `Assets`.

## Tecnologias Utilizadas
- **Excel** para criação do dashboard
- **Python** (opcional) para manipulação e análise dos dados

## Autor
Projeto desenvolvido para fins de análise de dados e visualização.
