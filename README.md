# ProjetoDio-CriandoBandodeDados

## 1ª Etapa - Criação do Banco de Dados
- Criação de uma instância na Azure para MySQL.
- Criar o Banco de dados com base disponível no github, fazendo a criação de tabelas e a inserção dos dados todos através do Bash do Cloud Shell com linguagem SQL.
- Integração do Power BI com MySQL no Azure.
- Verificar problemas na base a fim de realizar a transformação dos dados.

## 2ª Etapa - Transformação e tratamento dos dados
a)- Apenas um dos Colaboradores não tem números de referência em Super_ssn, e isso ocorre porque ele é o Gerente Geral e não tem ninguém acima dele.

b)- Todas as modificações e transformações de daods foram feitos usando o Power Query.

c)
- Descrição das Consultas - Organização de dados do banco de dados existente.
- Departments - Organização dos dados dos nomes dos departamentos existentes na empresa e os gerentes responsáveis.
- Dependents - Nome dos Colaboradores com seus respectivos dependentes.
- Departments/Locations - Os nomes dos departamentos e da cidade onde estão inseridos. Há cidades com mais de 1 departamento diferente e  o mesmo departamento presente em várias cidades diferentes.
- Employees - Consulta com todas as informações dos colaboradores.
- Projects - Consulta com todos os nomes dos projetos existentes, a cidade e o departamente onde estão inseridos.

d)
- Descrição das Consultas - Criação de Consultas Específicas para o Desafio.
- Employees/Department - Consulta mesclada com cada Colaborador e o Departamento/Cidade onde estão inseridos.
- Hours/Project - Consulta com os nomes dos projetos e quantas horas cada projeto está sendo trabalhado.
- Employees/Gerentes - Consulta junção com nome dos colaboradores e o nomes dos gerentes responsáveis.
- Projects/Employees/WorkHours - Consulta com quantas horas cada colaborar empreendeu em cada projeto.
- Gerentes/Associados - Nomes dos gerentes e o número de colaboradores associados a cada um deles.
- Employees/Hours Project - Nomes dos colaboradores e de quantas horas AO TODO eles empreenderam em projetos, sem diferenciar por projeto.

## 3ª Etapa
Criação de uma Relatório Básico Ilustrativo com os dados Transformados.

## IMAGENS

![Relatório Company-DesafioDIO-LeviMarra-1](https://github.com/LeviMarra/PowerBi-Projeto-Dio-Modulo3/assets/137719953/7513d190-8ab7-4c66-8c51-8b1a04c0936c)

![Relatório Company-DesafioDIO-LeviMarra-2](https://github.com/LeviMarra/PowerBi-Projeto-Dio-Modulo3/assets/137719953/70696a8d-ec2a-43fa-91af-e6968ceaaba1)

![Relatório Company-DesafioDIO-LeviMarra-3](https://github.com/LeviMarra/PowerBi-Projeto-Dio-Modulo3/assets/137719953/024d3bbb-f40b-4846-9c96-c80b520c164e)


