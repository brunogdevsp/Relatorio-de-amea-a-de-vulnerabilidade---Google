# Relatório de Ameaça de Vulnerabilidade

Este repositório contém a documentação e os artefatos produzidos durante o laboratório de avaliação de vulnerabilidades, realizado como parte do curso de **Cibersegurança Profissional do Google**, em parceria com a **Coursera** e o **CIEE**.

## 📌 Objetivo

O projeto tem como finalidade aplicar os conceitos de análise de risco e segurança da informação em um ambiente simulado, utilizando práticas recomendadas pelo framework **NIST SP 800-30 Rev. 1**. O foco principal é identificar, avaliar e mitigar ameaças relacionadas ao controle de acesso de um servidor de banco de dados.

## 🧠 Contexto

O sistema avaliado consiste em um servidor Linux com MySQL, operando com 128 GB de memória e conexões criptografadas via SSL/TLS. A análise considera o impacto de possíveis ameaças sobre os dados corporativos e a continuidade operacional.

## 🛡️ Avaliação de Risco

A tabela abaixo resume os principais riscos identificados:

| Fonte de Ameaça       | Evento de Ameaça                                         | Probabilidade | Gravidade | Risco |
|------------------------|----------------------------------------------------------|---------------|-----------|-------|
| Concorrente            | Infiltração para obtenção de dados sensíveis             | 1             | 3         | 3     |
| Funcionário Interno    | Vazamento acidental por e-mail ou compartilhamento indevido | 2             | 2         | 4     |
| Hacker Externo         | Ataque de ransomware ao servidor de banco de dados       | 3             | 3         | 9     |

## 🔧 Estratégia de Remediação

As ações propostas para mitigar os riscos incluem:

- Autenticação multifator (MFA)
- Controle de acesso baseado em funções (RBAC)
- Auditoria de logs e atividades
- Criptografia de dados em trânsito com **TLS**
- Lista de permissões de IP para acesso restrito

## 📚 Referências

- [NIST SP 800-30 Rev. 1 – Guide for Conducting Risk Assessments](https://csrc.nist.gov/publications/detail/sp/800-30/rev-1/final)
- [Google Cybersecurity Certificate](https://grow.google/certificates/cybersecurity/)
- [Coursera](https://www.coursera.org/)
- [CIEE](https://www.ciee.org.br/)

## 🧑‍💻 Autor

**BRUNO**  
Estudante de Cibersegurança | Google Career Certificate  
