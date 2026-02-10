# Livro Testes de Invasão

# Capítulo 1 – Avaliação de Vulnerabilidades com Nessus

## Contexto
Este laboratório faz parte do meu processo de aprendizado em cibersegurança,
com foco em **avaliação de vulnerabilidades** e **fundamentos de pentest**.

O experimento foi realizado em um **ambiente controlado de laboratório**, utilizando
máquinas virtuais para garantir segurança e ética durante os testes.

---

## Objetivo do laboratório
Compreender, na prática:

- o papel de um **scanner de vulnerabilidades**
- como interpretar resultados de risco (**CVSS**)
- a diferença entre **identificar vulnerabilidades** e **explorá-las**
- limites entre **scanner automatizado** e **pentest**

---

## Ambiente utilizado
- Sistema atacante: Kali Linux
- Sistema alvo: Metasploitable (máquina vulnerável de laboratório)
- Ferramenta de análise: Nessus Essentials
- Tipo de varredura: Basic Network Scan

---

## Metodologia
1. Configuração do Nessus no Kali Linux
2. Descoberta de host na rede local
3. Execução de varredura automatizada de vulnerabilidades
4. Análise dos resultados reportados pela ferramenta

⚠️ **Importante:**  
Nenhuma vulnerabilidade foi explorada.  
O laboratório teve caráter **exclusivamente analítico e educacional**.

---

## Principais resultados observados
A varredura identificou diversas vulnerabilidades classificadas como:

- Críticas
- Altas
- Médias

Exemplo de achado crítico:
- Sistema operacional desatualizado e fora de suporte
- Serviços inseguros expostos na rede

Esses resultados demonstram como ferramentas automatizadas auxiliam na
**identificação de riscos**, mas não realizam exploração por si só.

---

## Aprendizados
- Nessus é um **scanner**, não uma ferramenta de ataque
- Vulnerabilidade ≠ exploit
- CVSS representa **risco**, não certeza de invasão
- Scanner automatizado é parte inicial do processo de segurança

---

## Considerações finais
Este laboratório consolidou minha compreensão sobre o papel da
**avaliação de vulnerabilidades** dentro do ciclo de segurança da informação
e servirá como base para estudos futuros em exploração controlada e pentest.
