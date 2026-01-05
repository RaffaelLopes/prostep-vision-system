# prostep-vision-system
**Português** | 🇺🇸 [English](README_EN.md)

ProStep Vision System (Modelo de Exemplo)
📌 Sobre o Projeto

O ProStep Vision System é um modelo funcional de exemplo (Proof of Concept) desenvolvido para demonstrar a lógica, o fluxo e a viabilidade técnica de um sistema maior de qualidade industrial por conferência de montagem.

⚠️ Importante:
Este repositório NÃO representa o sistema final em produção.
Ele foi criado exclusivamente como modelo didático e demonstrativo, servindo como base para evolução de um projeto corporativo mais robusto.

O projeto completo e conceitual está descrito no documento:

Sistema de Qualidade por Conferência (SQC)
Autor: Rafael Lopes Ferreira

🎯 Objetivo do Modelo

Demonstrar, de forma prática, como um sistema pode:

Garantir conferência de montagem por step

Identificar falhas de processo (buracos entre steps)

Fornecer visibilidade em tempo real ao Gate da Qualidade

Registrar confirmações por matrícula, step e série

Apoiar a tomada de decisão no controle de qualidade

🧩 Escopo Deste Repositório

Este modelo contempla:

Interface Web (HTML + CSS + JavaScript)

Controle de acesso por perfil:

STEP (operadores)

GATE (qualidade)

Controle de turno

Meta de produção por turno

Dashboard com indicadores em tempo real

Sinalização visual:

🟢 Step conferido

🔴 Step não conferido (buraco no processo)

Histórico básico de confirmações em memória local (LocalStorage)

🔄 Fluxo Demonstrado no Sistema

Operador faz login informando:

Matrícula

Número de série

Step de atuação

O sistema exibe o checklist do step

Após conferência, o operador confirma o step

O Gate da Qualidade acompanha:

Confirmações em tempo real

Falhas entre steps

Evolução do turno

Ao encerrar o turno:

As informações são consolidadas

O turno é finalizado para novo ciclo

🧠 Projeto Maior (Visão Conceitual – SQC)

Este modelo é inspirado e baseado no projeto Sistema de Qualidade por Conferência (SQC), que em sua versão completa prevê:

Backend integrado a ERP / MES

Banco de dados relacional para rastreabilidade

Alertas automáticos (WhatsApp, e-mail)

Relatórios automáticos por turno, série e funcionário

Histórico permanente de qualidade

Acompanhamento por Team Leader e Qualidade

Redução de defeitos recorrentes por step

📄 Consulte o PDF do projeto SQC para a visão completa do sistema.

🛠️ Tecnologias Utilizadas (Modelo)

HTML5

CSS3

JavaScript (Vanilla)

LocalStorage (apenas para simulação)

Layout responsivo

🚧 Limitações Conhecidas

Por se tratar de um modelo de exemplo, este projeto:

Não utiliza backend

Não possui banco de dados real

Não possui autenticação segura

Não envia alertas reais

Não deve ser utilizado diretamente em ambiente produtivo

🚀 Próximos Passos (Evolução Natural)

Implementação de backend (Node.js / Java / .NET)

Integração com banco de dados

APIs para alertas automáticos

Relatórios exportáveis (Excel / PDF)

Controle de permissões por perfil

Auditoria completa de qualidade

👤 Autor

Rafael Lopes Ferreira
Projeto desenvolvido como estudo, protótipo funcional e base para evolução de um sistema corporativo de qualidade.
