# 🛡️ Construindo Minha Central de Estudos em IAM & Governança com Inteligência Artificial

Olá! Meu nome é **Eliel**, atuo como **Analista de Gestão de Acessos II** e criei este repositório para documentar meu projeto prático do desafio da DIO. 

Em vez de criar um caderno genérico apenas para cumprir tabela, decidi usar o **Google NotebookLM** para estruturar a minha própria esteira de especialização de carreira. O objetivo foi centralizar conteúdos complexos de Engenharia de Identidades (IAM), Governança (IAG), manipulação de dados e imersão em inglês corporativo em um único ecossistema de aprendizado ativo.

---

## 📚 Como organizei meus Cadernos de Estudos (Curadoria de Fontes)
Para não sobrecarregar a IA com informações inúteis, separei minha estrutura no NotebookLM em 4 pilares estratégicos, utilizando fontes oficiais de peso no mercado:

1. **Pilar 1: IAM & IAG (O Core Business)**
   - Alimentado com as documentações oficiais do **Microsoft Entra ID** (focado em *Acesso Condicional* e *PIM*) e a biblioteca conceitual da **SailPoint** para entender profundamente o ciclo de vida e engenharia de governança.
2. **Pilar 2: Engenharia de Dados Aplicada à Identidade**
   - Guias práticos de queries SQL (`INNER JOIN`, `GROUP BY`) voltados para auditoria e cruzamento de relatórios, além de estruturas de dados em JSON e Expressões Regulares (Regex) para limpeza de logs de acessos.
3. **Pilar 3: Automação no Espaço de Trabalho (VS Code & Git)**
   - Manuais de boas práticas de automação com Python/PowerShell e controle de versão com Git para começar a construir meu portfólio de scripts profissionais.
4. **Pilar 4: Inglês para Profissionais de Identidade**
   - Transcrições de episódios da série *The Office* para absorver o inglês corporativo falado no dia a dia de um escritório, além de especificações de protocolos globais (RFC do OAuth 2.0) para dominar os termos técnicos do mercado internacional.

---

## 🤖 Engenharia de Prompts & "Cicatrizes" do Processo (Troubleshooting)
O maior aprendizado desse desafio foi entender que uma IA só responde bem se você souber perguntar. 

### O Prompt que mudou o jogo:
Para testar o poder do meu caderno de governança, fiz a seguinte pergunta:
> *"Com base nos manuais de segurança fornecidos, crie um cenário prático onde um analista sênior detecta o acúmulo de privilégios (Privilege Creep) de um funcionário que mudou de área (Mover) e como estruturar uma matriz para mitigar isso."*

### Minhas Cicatrizes (O que deu errado e como corrigi):
No início, o NotebookLM me trazia respostas muito rasas e teóricas. Percebi que o problema era que eu estava alimentando a IA com artigos genéricos em português. 
**A solução:** Deletei as fontes secundárias e passei a usar apenas documentações oficiais e RFCs nativas em inglês (*en-us*). O nível técnico das respostas subiu drasticamente e, de quebra, me forçou a praticar a leitura técnica no idioma global.

---

## 📖 Meu Miniguia de Sobrevivência em IAM/IAG

### 🧠 Três conceitos que todo Analista de Elite precisa dominar:
* **Ciclo de Vida JML (Joiner, Mover, Leaver):** Gerenciar a entrada, movimentação e saída do colaborador. Automatizar o desligamento (*Leaver*) é a prioridade número um para evitar contas órfãs esquecidas na rede.
* **Segregação de Funções (SoD):** Garantir que a mesma pessoa não tenha acessos que permitam fraudes (ex: quem cria um fornecedor no sistema não pode ser o mesmo que aprova o pagamento).
* **Privilégio Mínimo (PoLP):** Dar ao usuário apenas o acesso estritamente necessário para ele trabalhar naquele momento, nem mais, nem menos.

### 🔍 Dicionário de Bolso (Termos em Inglês que uso direto):
* **Access Review / Access Certification:** Campanhas de revisão de acessos onde os gestores validam quem ainda precisa de permissões.
* **Privilege Creep:** O acúmulo silencioso de acessos antigos quando um funcionário muda de cargo e ninguém limpa os acessos anteriores.
* **Just-In-Time (JIT) Access:** Permissão administrativa temporária. Você se torna "admin" por 2 horas para resolver um problema e o acesso expira sozinho depois.

---
*Este projeto foi o pontapé inicial para transformar a forma como estudo e gerencio identidades no meu dia a dia técnico!*
