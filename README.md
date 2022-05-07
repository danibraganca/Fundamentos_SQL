# Análise de Vendas

- **Empresa**: sales.z
- **Contato**: Alex Souza
- **Email**: aasouzaconsult@gmail.com

-----

- ***Consultoria***: data.z
- ***Entrega do projeto em***: 08.05.2022
- ***Responsável pela entrega***: Daniela Bragança
- ***Necessidade do cliente (resumo)***: Análise da base de vendas, com o objetivo de responder as perguntas realizadas pelo cliente.


## Consultas


## Fase 1:

### Quantidade de dependentes
```sql
SELECT count(*) AS QtdDependentes FROM TbDependente;
```

Resultado:

![image](imagens/01.jpg)


### Quantidade de dependentes por sexo
```sql
SELECT SxDep, count(*) AS QtdDependentes FROM TbDependente GROUP BY SxDep;
```

Resultado:

![image](imagens/02.jpg)