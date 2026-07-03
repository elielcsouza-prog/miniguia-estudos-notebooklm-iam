# 🛡️ Treinando uma IA de Aprendizagem: Linha de Estudo em IAM, Dados & Governança

## 📋 Contexto e Objetivos
Este repositório foi desenvolvido como entrega para o desafio prático da plataforma DIO. O objetivo central é utilizar a Inteligência Artificial ativa, por meio do Google NotebookLM, para estruturar, organizar e acelerar uma linha de estudos de alta performance voltada para a especialização em Engenharia e Governança de Identidades e Acessos (IAM/IAG), integrando automação de dados e imersão em inglês técnico corporativo.

---

## 📚 Curadoria de Fontes (Data Sources)
Para alimentar o ecossistema no NotebookLM e garantir respostas de alta fidelidade técnica e regulatória, os cadernos temáticos foram populados com as seguintes fontes abertas oficiais:

1. **Pilar 1: IAM & IAG (The Core Business)**
   - Documentação Oficial do Microsoft Entra ID (Políticas de Acesso Condicional, PIM e Access Reviews).
   - SailPoint Identity Library (Conceitos de ciclo de vida JML e Segregação de Funções - SoD).
   - Diretrizes NIST SP 800-63 (Digital Identity Guidelines).

2. **Pilar 2: Identity Data Engineering**
   - Trilha de DQL SQL (W3Schools) focado em queries de auditoria (`SELECT`, `WHERE`, `INNER JOIN`).
   - Manuais de especificação estrutural de arquivos JSON/CSV e higienização de logs via Expressões Regulares (Regex).

3. **Pilar 3: Workspace Automation (VS Code & Git)**
   - Guias de configuração de ambiente e debugging para ambientes Python e PowerShell no VS Code.
   - Tutoriais oficiais do Git (Atlassian) para gerenciamento de histórico e versionamento de código.

4. **Pilar 4: English for Identity Professionals**
   - Transcrições textuais completas e roteiros de episódios da série corporativa *The Office* para absorção de inglês prático de escritório.
   - Especificações técnicas puras (RFC 6749 - OAuth 2.0 Framework) para domínio do vocabulário corporativo internacional.

---

## 🤖 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Durante a iteração e o treinamento da IA de aprendizagem, foram desenvolvidos prompts de alta contextualização e refinados após a análise das respostas:

### Prompt Estratégico de Teste:
> *"Com base nas fontes de segurança e governança fornecidas, crie um caso de uso prático onde um Analista de IAM Sênior identifica o acúmulo de privilégios (Privilege Creep) durante a movimentação interna de um colaborador (Mover). Apresente o script lógico de mitigação e as queries de auditoria."*

### Cicatrizes e Desafios Superados (Troubleshooting):
- **Desafio:** No início das interações, o NotebookLM gerava respostas operacionais superficiais e misturava termos técnicos genéricos quando as fontes incluídas eram em português.
- **Solução:** O escopo das fontes foi restringido estritamente para documentações nativas e especificações técnicas em inglês (*en-us*). Essa mudança elevou drasticamente o nível de maturidade da IA e forçou o aprendizado contínuo do inglês aplicado no ambiente de trabalho.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 🧠 Resumo Estruturado do Assunto:
- **JML (Joiner, Mover, Leaver):** Governança completa do ciclo de vida da identidade dentro de uma corporação. A automação eficiente deste fluxo elimina brechas críticas de segurança, blindando a organização contra vetores de ataque comuns.
- **SoD (Segregação de Funções):** Matriz de governança imposta para garantir que uma única identidade não possua privilégios conflitantes que permitam fraudes (ex: permissão de criar um fornecedor e aprovar o pagamento simultaneamente).
- **PoLP (Princípio do Privilégio Mínimo):** O pilar fundamental onde cada usuário, conta de serviço ou processo deve possuir apenas os acessos estritamente necessários para a execução de suas tarefas vigentes.

### 🔍 Glossário Técnico Essencial (Inglês Corporativo de IAM):
- **Access Certification / Access Review:** Campanhas periódicas obrigatórias de revisão e validação de direitos de acesso feitas pelos gestores.
- **Privilege Creep:** O acúmulo silencioso de permissões obsoletas que ocorre quando um funcionário muda de cargo ou departamento e seus acessos antigos não são revogados.
- **Just-In-Time (JIT) Access:** Concessão de privilégios elevados de forma temporária e sob fluxo de aprovação com expiração automática (PIM/PAM).

### 💾 Prompts Reutilizáveis para Revisões Futuras:
- `Crie uma tabela comparativa detalhada entre modelos RBAC e ABAC com cenários práticos de aplicação no Microsoft Entra ID.`
- `Escreva a estrutura lógica de um script em Python para ler um arquivo JSON de log e filtrar tentativas falhas de login.`
- `A partir das fontes de inglês corporativo, simule um diálogo de entrevista focado em perguntas de arquitetura de governança IAG.`

---
*Documentação desenvolvida como portfólio de evolução profissional.*
