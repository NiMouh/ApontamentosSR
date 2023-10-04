# Aula 2

Note: Perform static analysis testing you don't execute de code, on contrast with dynamic testing.

## SDL (Security Development Lifecycle)
Conjunto de práticas e diretrizes que visam melhorar a segurança de software durante todo o ciclo de desenvolvimento.

### Overview
1. Treino
2. Concepção do projeto
3. Análise e requisitos
4. Design detalhado e arquitetura
5. Implementação e testagem
6. Lançamento e suporte

## STRIDE approach
Este modelo de ameaças ajuda a enumerar as ameaças e possíveis modificações no design para eliminar/controlar o impacto:
1. **S**poofing Identity: fingir ser outra pessoa
2. **T**ampering with data: modificação maliciosa dos dados
3. **R**epudiation: negar uma ação
4. **I**nformation Disclosure: exposição de informação privada
5. **D**enial of Service: serviço inutilizável
6. **E**levation of priviledge: aumento de privilégios de acesso

## Estabelecer um padrão para o processo de resposta a incidents (IRP)
O plano deve incluir:
 - Quem contactar, caso exista uma emergência de segurança
 - Protocolo estabelecido para mitigação da vulnerabilidade
 - Planos para o codigo inserido de outros grupos dentro da organização e código de terceiros

## Análise de Risco (Architectual Risk Analysis)
Bastante semelhante ao Threat Modeling, mas com uma abordagem mais arquitetural. O objetivo é identificar as ameaças e vulnerabilidades do sistema, e avaliar o risco de cada uma. 

O **McGraw** propõe um processo de **3 passos**:
 - Análise de resistência a ataques: Explora ameaças conhecidas;
 - Análise de ambiguidade: Descobre ameaças novas;
 - Análise de fraquezas: Explora assumções de outros.

## SSD - Software Security Touchpoints
1. Rever código (com ou sem ferramentas)
2. Análise do risco arquitetónico
3. Testes de penetração de software
4. Testes com base no risco de segurança
5. Casos de abuso (ex.: inserção inválida de datas/outro tipo de entrada)
6. Requisitos de segurança
7. Operações de segurança (não apenas a nível de software)


## SAFECode - Software Assurane Forum for Excellence in Code
É uma organização que tem como objetivo melhorar a segurança de software. Para isso, desenvolveu um conjunto de práticas que devem ser seguidas para melhorar a segurança de software.

Estas são as práticas:
- Aplicação de requisitos de segurança
- Design
- Gestão de riscos de segurança que provêm de código de terceiros
- Teste e validação
- Gestão de constatações de segurança (através dos passos anteriores)
- Resposta e divulgação de vulnerabilidades
- Planeamento da implemtanção de segurança

**Sumário** dos processos no slide 26