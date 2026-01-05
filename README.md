# prostep-vision-system
**Português** | 🇺🇸 [English](README_EN.md)

O ProStep Vision System é um modelo funcional de sistema web desenvolvido para controle de qualidade por conferência de etapas (steps) em processos industriais.

Este projeto não representa o sistema final, mas sim um protótipo conceitual e técnico, criado para:

Validar regras de negócio

Demonstrar fluxo de controle por etapas

Servir como base de estudo e expansão para um projeto maior

O projeto completo, com visão de negócio, requisitos e escopo ampliado, está documentado nos PDFs disponíveis na pasta /docs
.

🎯 Objetivo

Demonstrar, de forma prática, como um sistema pode:

Controlar confirmações por Step

Identificar falhas de sequência (buracos entre steps)

Centralizar validações em um painel Gate

Gerar indicadores de conclusão por turno

Servir como base para um sistema corporativo maior

🧩 Estrutura do Sistema
🔹 STEP (Operação)

Checklist obrigatório por etapa

Confirmação apenas após interação completa

Indicadores visuais de status:

🟢 Confirmado

🔴 Pendência (quando há buraco)

🟠 Em andamento

🔹 GATE (Controle Central)

Início e encerramento de turno

Definição dinâmica da meta do turno

Visualização em tempo real das confirmações

Identificação automática de falhas entre steps

Dashboard consolidado por Step, não por série

📊 Dashboard do Turno

O dashboard foi projetado para refletir a realidade operacional, considerando:

A meta do turno aplicada independentemente da série

A conclusão baseada em:

Quantidade de confirmações por Step

Total esperado = meta × número de steps

Atualização automática ao:

Alterar a meta

Confirmar steps

Corrigir pendências via Gate

📁 Estrutura do Projeto
prostep/
│
├── css/          # Estilos do sistema
├── js/           # Lógica do sistema (Gate, Step, Sessões)
├── pages/        # Páginas HTML
├── data/         # Dados auxiliares (JSON)
├── docs/         # Documentação do projeto (PDF PT-BR e EN)
│
├── README.md     # Documentação em Português
├── README_EN.md  # Documentation in English

📄 Documentação do Projeto

A documentação conceitual e funcional completa está disponível em:

📘 Português:
docs/Sistema de Qualidade por Conferência.pdf

📗 English:
docs/System_Quality_Conference_SQC_EN.pdf

Esses documentos descrevem o projeto maior, do qual este repositório é apenas um modelo demonstrativo.

⚠️ Aviso Importante

Este repositório é um projeto de exemplo / prova de conceito.
Ele foi desenvolvido para estudo, validação de ideias e demonstração técnica, não devendo ser utilizado diretamente em ambiente produtivo sem adaptações.

👤 Autor

Rafael Lopes Ferreira
