# aprendizado-dados-
"Exercícios diários de SQL e lógica de programação - Focada em Engenharia de Dados."
SQL
-- Script de acompanhamento de evolução técnica
-- Criado para o desafio Thomson Reuters

CREATE TABLE Evolucao_Carreira (
    Habilidade VARCHAR(50),
    Nivel_Conhecimento VARCHAR(20)
);

INSERT INTO Evolucao_Carreira VALUES ('Lógica de Programação', 'Em Construção');
INSERT INTO Evolucao_Carreira VALUES ('SQL Básico', 'Iniciante');
INSERT INTO Evolucao_Carreira VALUES ('Engenharia de Dados', 'Estudando');

SELECT * FROM Evolucao_Carreira;
