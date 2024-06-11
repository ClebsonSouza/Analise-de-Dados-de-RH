## Analise-de-Dados-de-RH

### *Exemplo utilizado no curso da Data Science Academy

### Projeto de Análise Descritiva, Diagnóstica e Estatística de Dados de Recursos Humanos (RH) Utilizando Python
Este projeto consiste em uma análise completa dos dados de Recursos Humanos (RH), abrangendo aspectos descritivos, diagnósticos e estatísticos. Foram utilizados dados reais, disponibilizados publicamente, e aplicadas diversas técnicas de análise de dados.

Definição do Problema de Negócio:
Uma empresa de consultoria especializada em Big Data e Data Science deseja contratar Cientistas de Dados dentre os indivíduos que obtiverem aprovação em determinados cursos oferecidos pela empresa.

Dado o grande número de inscrições para o treinamento, a empresa busca identificar quais candidatos têm real interesse em trabalhar na empresa após a conclusão do treinamento, e quais estão apenas utilizando o treinamento como um meio de reintegração ao mercado de trabalho.

O objetivo é selecionar profissionais com o perfil mais adequado, visando reduzir os custos e o tempo de contratação, além de aprimorar a qualidade do treinamento, o planejamento dos cursos e a categorização dos candidatos.

Este conjunto de dados foi desenvolvido para compreender os fatores que levam um indivíduo a deixar o emprego atual.

Dicionário:
enrollee_id : Unique ID for candidate

city: City code

city_ development _index : Developement index of the city (scaled)

gender: Gender of candidate

relevent_experience: Relevant experience of candidate

enrolled_university: Type of University course enrolled if any

education_level: Education level of candidate

major_discipline :Education major discipline of candidate

experience: Candidate total experience in years

company_size: No of employees in current employer's company

company_type : Type of current employer

lastnewjob: Difference in years between previous job and current job

training_hours: training hours completed

target: 0 – Not looking for job change, 1 – Looking for a job change

### Com base em nossa análise, identificamos as variáveis mais relevantes para selecionar um bom candidato:

1 - Índice de Desenvolvimento da cidade onde reside o candidato.

2 - Tempo de experiência profissional.

3 - Matriculado ou não em um curso universitário.

4 - Presença de experiência relevante.

5 - Nível educacional.

6 - Tipo de empresa onde o candidato trabalha ou trabalhou.

7 - Especialização na graduação (quando aplicável).

### As variáveis consideradas irrelevantes para a análise são:

1 - ID do candidato.

2 - Código da cidade do candidato (o nome da cidade seria relevante).

3 - Gênero.

4 - Data da última vez que o candidato esteve empregado.

5 - Tamanho da empresa (quando aplicável).

6 - Total de horas de treinamento.

### Recomendações:

O RH pode desenvolver um método de coleta de dados para obter outras informações que melhorem a qualidade dos dados e tornem a análise mais precisa.

O RH pode procurar candidatos de cidades com baixo índice de desenvolvimento urbano, sem experiência relevante, com nível de educação superior e menor experiência de trabalho, para encontrar aqueles que estão em busca de emprego.

O RH pode compactar o treinamento, pois muitas pessoas não necessitam de um longo período para completá-lo.
