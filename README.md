# 📊 **Análise de Turnover e Perfis de Colaboradores - Projeto de Dados**

## **Contexto**  
Este projeto foi desenvolvido como um estudo de caso para um departamento fictício de Recursos Humanos. A análise foi baseada em dados simulados de uma empresa hipotética, com o objetivo de explorar padrões e responder a perguntas estratégicas relacionadas à retenção de talentos e gestão de pessoas.  
Os dados fornecidos incluem informações de 200 colaboradores, abrangendo aspectos como tempo de casa, avaliações de desempenho, satisfação no trabalho e histórico de desligamentos. A análise busca identificar insights que poderiam embasar decisões em empresas reais.

## **Problemas identificados na base**  
Na primeira etapa, foram observadas inconsistências nos dados simulados, como:  
- Colaboradores com status "Desligado" sem data de demissão.  
- Supersalários atribuídos a cargos de nível inicial.  
- Registros com status ativo, mas com data de desligamento.  
- Campos fora dos padrões da política organizacional.  
- Cálculo incorreto do tempo de casa.  
- Status de desligado sem motivo associado.

  ![Logo do GitHub](https://miro.medium.com/v2/resize:fit:828/format:webp/1*cjuFsijlbgtHHGUJ7V9FWQ.jpeg)

Esses problemas foram ajustados na base revisada, garantindo maior confiabilidade na análise.

📊 [Click aqui para Acessar o Painel deste projeto no Power BI](https://app.powerbi.com/view?r=eyJrIjoiODE4Y2Q3OWEtOTg0OC00NjI1LWI4NjMtMTY0NDNmMzYzNDFkIiwidCI6IjgxY2RjMzU5LTkwYWQtNGJjOC1iNTUyLTNlZjI1NzBhY2ZkMyJ9)
---
## 1️⃣ **Qual é a distribuição de colaboradores por departamento?**  
Os colaboradores estão distribuídos da seguinte forma:  
- Operações: 38  
- Marketing: 35  
- TI: 35  
- Vendas: 34  
- Financeiro: 33  
- RH: 25  

*A maior concentração está em Operações, o que pode refletir o papel estratégico deste departamento na estrutura da empresa. Já o RH, com a menor quantidade, pode indicar a necessidade de expansão para suportar a gestão de um quadro maior de colaboradores.* 

## 2️⃣ **Qual o percentual de turnover total na empresa?**  
A taxa de turnover é **28%**, com 144 colaboradores ativos e 56 desligados. 

*Esse índice, embora comum em algumas indústrias, pode ser reduzido com políticas que abordem as principais causas de desligamento, como desempenho e retenção de talentos estratégicos.*

## 3️⃣ **Qual o tempo médio de permanência dos colaboradores por departamento?**  
- **Marketing, RH e Operações**: 4 anos.  
- **Financeiro e Vendas**: 5 anos.  
- **TI**: 6 anos (o maior tempo médio).  

*O tempo médio de 6 anos no TI sugere maior estabilidade, possivelmente devido a incentivos específicos ou à natureza técnica do trabalho. Já áreas como Marketing e Operações podem demandar ações de retenção para aumentar a permanência dos colaboradores.*

## 4️⃣ **Existe diferença na taxa de turnover entre gêneros?**  
- Feminino: 31%  
- Masculino: 28%  
- Não binário: 27%  
- Trans: 13%  

*O turnover é menor entre pessoas trans, mas é necessário investigar fatores contextuais.*

## 5️⃣ **Qual o impacto da satisfação no trabalho no turnover?**  
Apesar de uma correlação quase nula, fatores como clima organizacional e oportunidades de crescimento podem mediar a relação.  

*Embora a satisfação declarada não mostre impacto direto, fatores qualitativos como liderança e reconhecimento devem ser investigados para uma abordagem mais abrangente de retenção.*

## 6️⃣ **Existe correlação entre avaliação de desempenho e desligamento?**  
Há uma relação negativa, indicando que colaboradores com melhores notas têm menor probabilidade de desligamento.  

*Fortalecer os programas de capacitação e desenvolver planos de melhoria de desempenho pode ser uma estratégia eficaz para reduzir desligamentos por baixo desempenho.*

## 7️⃣ **Qual a relação entre escolaridade e taxa de turnover?**  
- **Superior**: 39%  
- **Ensino Médio**: 28%  
- **Pós-graduação**: 18%  

*O turnover mais alto entre colaboradores com ensino superior pode estar ligado a expectativas maiores de crescimento ou à competitividade do mercado. Já os profissionais com pós-graduação apresentam maior retenção, possivelmente devido a cargos mais estratégicos e benefícios alinhados ao perfil.*

## 8️⃣ **Qual é o salário médio por departamento e gênero?**  
Os salários médios por gênero são:  
- **Masculino**: R$ 9.445  
- **Feminino**: R$ 8.882  
- **Não binário**: R$ 7.009  
- **Trans**: R$ 4.556  

Os salários médios por setores são:  
- **T.I**: R$ 9.375  
- **RH**: R$ 9.282  
- **Financeiro**: R$ 9.030  
- **Vendas**: R$ 8.574  
- **Operações**: R$ 8.309  
- **Marketing**: R$ 7.573  

*As diferenças salariais por gênero são claras, com destaque para a discrepância entre pessoas trans e outros grupos. Além disso, os setores de T.I. e RH apresentam salários mais altos. É crucial investigar essas desigualdades para promover equidade salarial e inclusão.*

## 9️⃣ **Qual é a principal causa de desligamento na empresa?**  
Com o uso de **Pareto**, identificamos que as principais causas de desligamento foram:  
- Desempenho: 32 desligamentos (60%).  
- Pedido Próprio: 12 desligamentos (22%).  
- Reestruturação: 7 desligamentos (12%).  
- Aposentadoria: 5 desligamentos (6%).  

*Os dois primeiros motivos acumulam 82% dos desligamentos, sugerindo a necessidade de ações voltadas para desempenho e retenção de colaboradores-chave.*

## 🔟 **Quais departamentos possuem as maiores taxas de turnover?**  
- **Operações**: 34%  
- **Vendas**: 32%  
- **RH**: 32%  

*As maiores taxas estão em áreas operacionais e de vendas, que costumam ter rotatividade elevada devido a altas demandas e competitividade. Implementar ações de suporte e valorização nessas áreas pode ajudar a mitigar esse cenário.

## **Recomendações**  
- Investir em capacitação e programas de desenvolvimento pode reduzir desligamentos por desempenho, que representam a maior parte dos desligamentos.  
- As disparidades salariais, especialmente para pessoas trans, indicam a necessidade de ajustes nas políticas de remuneração e maior atenção à inclusão e equidade.  
- Departamentos como Operações e Vendas apresentam os maiores índices de desligamento. Recomenda-se investigar possíveis sobrecargas de trabalho e melhorar o suporte às equipes.  
- Cada grupo demográfico possui desafios específicos, como gênero ou escolaridade. Estruturar políticas personalizadas pode melhorar o engajamento e retenção de talentos.

Este estudo demonstra como análises em bases fictícias podem simular o impacto de decisões baseadas em dados, oferecendo aprendizados aplicáveis a cenários reais.

📊 [Acesse o Painel deste projeto no Power BI](https://app.powerbi.com/view?r=eyJrIjoiODE4Y2Q3OWEtOTg0OC00NjI1LWI4NjMtMTY0NDNmMzYzNDFkIiwidCI6IjgxY2RjMzU5LTkwYWQtNGJjOC1iNTUyLTNlZjI1NzBhY2ZkMyJ9)
---
## 🧮 **Códigos Utilizados**
```dax
Tempo_de_Casa = 
VAR DataDemissao = 
    IF(
        ISBLANK([Data_Demissão]),
        TODAY(),  // Se a data de demissão estiver em branco, usa a data atual.
        [Data_Demissão]
    )
RETURN
    DATEDIFF([Data_Admissão], DataDemissao, YEAR)  // Calcula o tempo de casa em anos.
```
```dax
Contagem_Pessoas = COUNTROWS(Base_Rh)  // Conta o número total de registros na tabela Base_Rh.
```
```dax
Salario_Medio = AVERAGE(Base_Rh[Salário])  // Calcula a média dos salários na tabela Base_Rh.
```

```dax
Turnover_Total = 
DIVIDE(
    COUNTX(FILTER(Base_Rh, Base_Rh[Status] = "Desligado"), Base_Rh[ID_Colaborador]),  // Conta o número de colaboradores desligados.
    COUNT(Base_Rh[ID_Colaborador]),  // Conta o número total de colaboradores.
    0  // Retorna 0 caso a divisão resulte em erro (como divisão por zero).
)
```
