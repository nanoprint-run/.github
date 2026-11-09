# Nanoprint

Plataforma de execução de micro-features e foco profundo para desenvolvedores, integrada ao ecossistema de controle de versão e gestão de tarefas.

## Visão Geral
O nanoprint é um SaaS criado para eliminar a fricção administrativa e a perda de foco no desenvolvimento de software. Em vez de painéis corporativos complexos, a ferramenta oferece um fluxo de execução atômico baseado em blocos de alta concentração de 25 minutos (sprints de micro-features). Ele conecta diretamente a atividade local do desenvolvedor no terminal aos sistemas de rastreabilidade e gestão de projetos, reduzindo interrupções e mantendo o contexto de trabalho intacto.

## Funcionalidades Principais
- Sprints de Micro-Features: Decompõe demandas complexas em tarefas atômicas de curta duração, protegendo o desenvolvedor contra interrupções e fadiga de contexto.
- Smart Commits e Automação de Estado: Sincroniza automaticamente o progresso do fluxo de trabalho por meio de convenções de commit (ex.: feat: SCRUM-1), realizando transições de status sem necessidade de acessar interfaces externas.
- Auditoria e Integridade de Dados: Trilha de auditoria imutável que registra alterações críticas, sessões e commits, garantindo conformidade e rastreabilidade em ambientes corporativos.
- Gamificação e Métricas de Produtividade: Sistema de pontuação (XP), sequências de entrega (streaks) e estatísticas consolidadas para reforçar hábitos consistentes de engenharia.

## Arquitetura e Pilha Tecnológica
- Backend: API RESTful de alta performance em .NET (C#).
- Persistência: Banco de dados relacional PostgreSQL, com modelagem normalizada para auditoria e relatórios de desempenho.
- Frontend: Aplicação web em Blazor, com interface limpa, minimalista e de baixa latência.
- CLI: Ferramenta de linha de comando multiplataforma integrada ao terminal para controle local de sessões e envio de métricas.

## Distribuição e Instalação da CLI
A CLI do nanoprint é distribuída de forma segura por meio dos binários oficiais publicados nos Releases da organização. Para instalar a ferramenta no ambiente de desenvolvimento, acesse a página de lançamentos ou utilize os scripts de instalação automatizados.
