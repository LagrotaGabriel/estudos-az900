#### **Alta disponibilidade**
Está associada ao tempo que o nosso provider nos garante que o nosso serviço estará disponível

> SLA - Service level agreement / Acordo de nível de serviço

Se aquele item ficar indisponível por mais tempo do que o que consta no SLA, teremos um reembolso de crédito em nossa conta.

A microsoft nos garante que se estamos utilizando um serviço que tem disponibilidade X, se aquele serviço ficar indisponível por mais tempo, seremos reembolsados em nossa fatura
#### **Tolerância a falhas**
Ainda que meu serviço ficar indisponível em uma "ponta", eu ainda vou ter ele funcionando. Ou seja, o meu usuário não percebe que aquele serviço está fora. 

Quando falamos de uma região, ela conta com pelo menos 3 data centers. Se eu coloco um modelo de serviço que replica entre esses 3 data centers e um deles ficar fora, meu usuário não vai sentir esse problema, por que ainda terão 2 ativos.
#### **Escalabilidade**
Está associada a quando vamos alterar recursos para atender a uma demanda computacional.
#### **Elasticidade**
Podemos dizer que vamos começar com duas máquinas e quando essas máquinas chegarem a 90% de recursos computacionais consumidos, vamos "crescer" mais duas máquinas

>Black Friday é a melhor forma de lembrarmos desse conceito.
#### **Alcance global**
Posso criar recursos em vários lugares do mundo que possuam data centers.
#### **Capacidade de latência do cliente**
#### **Agilidade**
#### **Considerações sobre custo preditivo**
Se trata da capacidade de prever gastos e despesas
#### **Recuperação de desastre**
Quando tive um problema, meu ambiente acabou precisando de um DR (Disaster recovery) mas a gente precisa subir nosso ambiente em outra região.

> Estamos com máquinas no Brasil, onde ocorreu uma catástrofe. Então temos réplicas nos EUA que serão utilizadas

> Não confundir com tolerância a falhas
#### **Segurança**