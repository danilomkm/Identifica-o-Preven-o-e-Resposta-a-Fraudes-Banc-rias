# Identifica-o-Preven-o-e-Resposta-a-Fraudes-Banc-rias
Projeto desenvolvido como parte do desafio da DIO, utilizando Inteligência Artificial e o NotebookLM como ferramentas de apoio à aprendizagem ativa.
📌 Sobre o Projeto

As fraudes bancárias estão entre os principais problemas relacionados à segurança digital. Com a popularização dos aplicativos bancários, pagamentos instantâneos e serviços financeiros digitais, os criminosos passaram a utilizar diferentes técnicas para obter informações, manipular vítimas e realizar transações não autorizadas.

Este projeto tem como objetivo estudar os principais tipos de fraudes bancárias digitais, compreender como elas funcionam e identificar medidas que podem ser utilizadas para prevenção, detecção e resposta.

O NotebookLM foi utilizado como ferramenta de apoio para organizar fontes, formular perguntas, comparar informações e consolidar o conhecimento adquirido.

🎯 Objetivos
Objetivo geral

Compreender os principais tipos de fraude bancária digital, suas técnicas de execução e formas de prevenção.

Objetivos específicos
Identificar os principais tipos de golpes bancários;
Compreender o funcionamento da engenharia social;
Estudar golpes envolvendo phishing;
Entender o funcionamento de falsas centrais de atendimento;
Analisar riscos relacionados ao roubo de credenciais;
Compreender conceitos relacionados a transações fraudulentas;
Identificar medidas de prevenção;
Entender o que fazer após identificar uma possível fraude;
Utilizar IA para organizar e revisar conhecimentos sobre segurança financeira.
📚 Curadoria de Fontes

Foram priorizadas fontes oficiais e instituições reconhecidas para reduzir o risco de utilização de informações incorretas.

1. Banco Central do Brasil

O Banco Central disponibiliza informações relacionadas à segurança, golpes, fraudes e utilização do sistema financeiro.

🔗 https://www.bcb.gov.br/

A fonte foi utilizada para compreender:

Segurança no sistema financeiro;
Pix;
Mecanismos de segurança;
Fraudes e golpes;
Orientações aos usuários.
2. FEBRABAN

A Federação Brasileira de Bancos disponibiliza materiais educativos relacionados à segurança bancária e aos principais golpes praticados contra clientes.

🔗 https://portal.febraban.org.br/

Conteúdos estudados:

Phishing;
Engenharia social;
Falsa central;
Golpes por telefone;
Golpes envolvendo aplicativos;
Segurança de informações bancárias.
3. CERT.br

O Centro de Estudos, Resposta e Tratamento de Incidentes de Segurança no Brasil disponibiliza materiais educativos sobre segurança na Internet.

🔗 https://www.cert.br/

A fonte foi utilizada para estudar:

Phishing;
Fraudes;
Senhas;
Engenharia social;
Segurança digital;
Incidentes de segurança.
4. NIC.br

O Núcleo de Informação e Coordenação do Ponto BR disponibiliza materiais relacionados à segurança e ao uso consciente da Internet.

🔗 https://www.nic.br/

Utilização:

Segurança digital;
Privacidade;
Fraudes online;
Boas práticas para usuários.

🧠 Engenharia de Prompts

Durante o estudo foram testadas diferentes formas de elaborar perguntas.

Prompt 01 — Resumo simples

"Explique os principais conceitos de defesa cibernética presentes nas fontes."

Resultado

A resposta apresentou uma visão geral, porém ficou muito abrangente.

Problema identificado

O conteúdo não possuía profundidade suficiente e misturava diferentes conceitos.

Melhoria

Foi necessário especificar o objetivo, o nível de conhecimento e solicitar referências às fontes.

Prompt 02 — Resposta estruturada

"Com base exclusivamente nas fontes fornecidas, explique os principais conceitos relacionados à detecção e resposta a incidentes. Organize a resposta em tópicos, apresente exemplos práticos e indique qual fonte fundamenta cada conceito."

Resultado

A resposta ficou mais organizada e permitiu relacionar os conceitos às respectivas fontes.

Aprendizado

Quanto mais específico é o objetivo do prompt, maior a possibilidade de obter uma resposta útil para estudo.

Prompt 03 — Comparação entre frameworks

"Compare o NIST CSF 2.0 e o MITRE ATT&CK. Explique a finalidade de cada um, suas principais diferenças e como poderiam ser utilizados em conjunto por uma equipe SOC."

Resultado esperado

A comparação permitiu compreender que os frameworks possuem objetivos diferentes:

NIST CSF: orientação para gerenciamento e redução de riscos;
MITRE ATT&CK: conhecimento estruturado sobre táticas e técnicas de adversários;
SOC: pode utilizar os dois de maneira complementar.
Prompt 04 — Cenário de SOC

"Considere um cenário em que um usuário recebeu um e-mail de phishing e forneceu suas credenciais. Com base nas fontes disponíveis, descreva como uma equipe SOC poderia identificar, analisar, responder e aprender com esse incidente."

Resultado

O cenário permitiu transformar conceitos teóricos em uma situação prática.

Fluxo analisado:

Phishing → Comprometimento → Detecção → Investigação → Contenção → Erradicação → Recuperação → Lições aprendidas

🩹 "Cicatrizes" do Processo

Durante a utilização da IA foram identificadas algumas dificuldades.

1. Prompts muito genéricos

Perguntas como:

"Explique cybersecurity."

geraram respostas muito amplas.

Correção: especificar tema, nível de profundidade, formato e fontes.

2. Excesso de informações

Algumas respostas apresentavam muitos conceitos simultaneamente.

Correção: dividir o estudo em perguntas menores.

3. Necessidade de validação

Uma resposta gerada pela IA não deve ser considerada automaticamente verdadeira.

Correção: solicitar que a resposta seja baseada nas fontes carregadas e verificar os conceitos diretamente nos documentos.

4. Diferença entre frameworks

Foi inicialmente possível confundir a finalidade do NIST CSF com a do MITRE ATT&CK.

Correção: realizar uma consulta específica de comparação.

📖 Miniguia de Estudos
1. Cybersecurity Risk

O gerenciamento de riscos busca compreender quais ativos precisam ser protegidos, quais ameaças podem afetá-los e quais medidas podem reduzir os impactos.

Uma forma simplificada de visualizar:

Ativo → Ameaça → Vulnerabilidade → Risco → Controle → Monitoramento

2. NIST CSF 2.0

O NIST CSF 2.0 fornece uma estrutura para organizar resultados relacionados à segurança cibernética e ao gerenciamento de riscos.

Suas funções principais são:

Govern

Estabelece e orienta a estratégia de gerenciamento de riscos.

Identify

Identificação dos riscos, ativos e contexto organizacional.

Protect

Implementação de medidas de proteção.

Detect

Identificação de possíveis eventos de cybersecurity.

Respond

Ações realizadas diante de um incidente.

Recover

Restauração das capacidades afetadas e melhoria após o incidente.

3. MITRE ATT&CK

O MITRE ATT&CK permite estudar o comportamento dos adversários através de táticas e técnicas.

Exemplo simplificado:

Initial Access

↓

Execution

↓

Persistence

↓

Privilege Escalation

↓

Credential Access

↓

Discovery

↓

Lateral Movement

↓

Collection

↓

Command and Control

↓

Exfiltration / Impact

Uma equipe SOC pode utilizar esse conhecimento para melhorar regras de detecção, investigação e threat hunting.

4. Segurança de Aplicações — OWASP

O OWASP Top 10 apresenta categorias importantes de riscos relacionados a aplicações web.

Entre os conceitos importantes estão:

Controle de acesso;
Falhas criptográficas;
Injection;
Configurações inseguras;
Componentes vulneráveis;
Falhas de autenticação;
Logging e monitoramento;
SSRF.

Um ponto importante aprendido foi que o OWASP Top 10 funciona principalmente como um documento de conscientização e ponto de partida, não como uma metodologia completa de testes de segurança.

5. Resposta a Incidentes

A resposta a incidentes deve ser planejada antes que um incidente aconteça.

Uma estrutura simplificada:

Preparação

Definir processos, responsáveis, ferramentas e procedimentos.

Detecção

Identificar sinais de comportamento suspeito.

Análise

Investigar evidências e determinar o que aconteceu.

Contenção

Reduzir ou interromper o impacto do incidente.

Erradicação

Remover a causa ou presença do atacante.

Recuperação

Restaurar os serviços afetados.

Lições aprendidas

Documentar o incidente e implementar melhorias.

A CISA destaca a importância de um plano formal de resposta a incidentes, incluindo papéis, responsabilidades e atividades antes, durante e após um incidente.

📚 Glossário
Termo	Definição
SOC	Security Operations Center, equipe responsável pelo monitoramento e resposta de segurança.
SIEM	Plataforma utilizada para coletar, correlacionar e analisar eventos e logs de segurança.
Threat Hunting	Busca proativa por sinais de comprometimento ou comportamento malicioso.
IOC	Indicator of Compromise, evidência que pode indicar comprometimento.
TTP	Táticas, técnicas e procedimentos utilizados por atacantes.
MITRE ATT&CK	Base de conhecimento sobre comportamentos e técnicas de adversários.
NIST CSF	Framework para gerenciamento de riscos de cybersecurity.
Vulnerabilidade	Fraqueza que pode ser explorada por uma ameaça.
Exploit	Código, técnica ou método utilizado para explorar uma vulnerabilidade.
Phishing	Técnica de engenharia social utilizada para induzir vítimas a realizar ações maliciosas.
Incident Response	Processo de preparação, detecção, análise, contenção e recuperação diante de incidentes.
SIEM	Sistema de gerenciamento e correlação de eventos e informações de segurança.
Blue Team	Equipe responsável principalmente pela defesa e monitoramento do ambiente.
Threat Intelligence	Informações utilizadas para compreender ameaças e apoiar decisões de segurança.
Log	Registro de eventos gerados por sistemas, aplicações ou dispositivos.
♻️ Prompts Reutilizáveis
Prompt de resumo

Com base exclusivamente nas fontes fornecidas, explique [TEMA] de forma didática, utilizando exemplos práticos e destacando os conceitos mais importantes para uma pessoa que está estudando Defesa Cibernética.

Prompt para revisão

Crie uma revisão de [TEMA] contendo os 10 conceitos mais importantes, erros comuns de entendimento e exemplos práticos.

Prompt para SOC

Considere um cenário de SOC envolvendo [INCIDENTE]. Explique como identificar, investigar, conter e responder ao incidente, relacionando as etapas aos frameworks apresentados nas fontes.

Prompt MITRE ATT&CK

Analise o cenário [CENÁRIO] e identifique quais táticas e técnicas do MITRE ATT&CK poderiam estar relacionadas ao comportamento observado. Explique o motivo de cada associação.

Prompt NIST

Relacione o cenário [CENÁRIO] às funções do NIST CSF 2.0. Explique quais ações poderiam ser realizadas em cada etapa.

Prompt de comparação

Compare [FRAMEWORK A] e [FRAMEWORK B] utilizando exclusivamente as fontes fornecidas. Apresente objetivo, vantagens, limitações, diferenças e possíveis aplicações em uma equipe de segurança.

Prompt de entrevista

Crie 10 perguntas de entrevista para uma vaga de Analista SOC sobre [TEMA]. Depois apresente respostas-modelo baseadas nas fontes estudadas.

Prompt de aprofundamento

Identifique quais conceitos relacionados a [TEMA] ainda precisam ser estudados para alcançar um nível intermediário. Organize os assuntos em ordem de prioridade.

💡 Principais Aprendizados

O principal aprendizado deste projeto foi perceber que a Inteligência Artificial pode ser utilizada como uma ferramenta de aprendizagem ativa, e não somente como um mecanismo para gerar respostas.

A qualidade do resultado depende diretamente de:

Qualidade das fontes + qualidade do prompt + capacidade de validação crítica

Também foi possível perceber que diferentes frameworks podem ser complementares.

Por exemplo:

NIST CSF

→ ajuda a estruturar o gerenciamento de riscos.

MITRE ATT&CK

→ ajuda a compreender o comportamento dos adversários.

OWASP

→ auxilia na identificação e conscientização sobre riscos de aplicações.

CISA / Incident Response

→ contribui para estruturar a preparação e resposta a incidentes.

🚀 Conclusão

A construção deste caderno temático permitiu consolidar conceitos fundamentais de Defesa Cibernética e, ao mesmo tempo, desenvolver habilidades de pesquisa, curadoria de fontes, engenharia de prompts e pensamento crítico.

O NotebookLM foi utilizado como ferramenta de apoio para organizar e explorar as fontes, enquanto a validação das informações permaneceu como responsabilidade do estudante.

Esse processo demonstra que ferramentas de IA podem potencializar o aprendizado quando utilizadas de forma crítica, estruturada e baseada em fontes confiáveis.

👨‍💻 Autor

Danilo

Estudante de Defesa Cibernética

Interesses:

Cybersecurity
SOC
Blue Team
Pentest
Threat Intelligence
Segurança de Redes
Cloud Security
