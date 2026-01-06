🧑‍🏭 Acesso ao Painel de STEP (Operação)
💻 Ambiente de Operação

O ProStep Vision System foi desenvolvido para utilização em estações de trabalho (computadores desktop ou notebooks), normalmente disponíveis na linha de produção ou em áreas de controle.

Requisitos mínimos:

Computador ou notebook

Navegador web atualizado (Chrome, Edge ou Firefox)

Conexão local para acesso ao sistema

JavaScript habilitado

⚠️ O uso em dispositivos móveis (celulares ou tablets) não é recomendado, pois a interface foi projetada para telas maiores.

Acesso ao sistema:
https://prostepvision-system.vercel.app/


📌 Para fins de demonstração e validação do fluxo do sistema, recomenda-se abrir o sistema em mais de uma aba ou janela do navegador, permitindo a visualização simultânea do painel STEP e do painel GATE.

✔️ Quem deve usar (STEP)

Operadores responsáveis pela execução de um Step específico do processo produtivo.

Cada operador atua apenas no Step selecionado no momento do login.

📝 Como preencher o login (STEP)

Na tela inicial do sistema, preencha os campos da seguinte forma:

🔹 Matrícula

Informe uma matrícula válida de operador de Step

As matrículas seguem um padrão numérico, por exemplo:

111220, 111221, 111222, 111223, ...


As matrículas permitidas estão definidas no arquivo:

data/matricula.json

🔹 Número de Série

Informe o número de série da unidade que está sendo trabalhada

Apenas números de série cadastrados no arquivo:

data/series-validas.json


serão aceitos pelo sistema

🔹 Step

Selecione o Step correspondente à operação que será executada

Cada operador deve atuar somente no Step selecionado

▶️ Acesso

Após o preenchimento correto dos campos, clique em Login.

📌 Caso algum dos dados esteja incorreto ou não autorizado, o sistema bloqueará o acesso.

🖥️ Tela de Operação (STEP)

Após o login, o operador terá acesso ao painel de operação, que contém:

Checklist obrigatório do Step selecionado

Indicadores visuais de status de todos os Steps

Botão Confirmar

Regras importantes:

Todos os itens do checklist devem ser marcados

O turno deve estar ativo (iniciado pelo GATE)

Somente após essas condições o botão Confirmar será liberado

Ao confirmar o Step:

O Step é registrado no sistema

A confirmação é enviada automaticamente para o painel GATE

🛂 Acesso ao Painel GATE (Controle Central)
✔️ Quem deve usar (GATE)

Responsável pelo controle de qualidade e acompanhamento geral do processo produtivo.

🔑 Regra especial de acesso ao GATE

O painel GATE possui uma matrícula exclusiva:

222222


⚠️ Nenhuma outra matrícula possui permissão para acessar o GATE.

📝 Como preencher o login (GATE)

Na tela de login, preencha os campos da seguinte forma:

🔹 Matrícula

Informe obrigatoriamente:

222222

🔹 Número de Série

Não preencher

O GATE não utiliza número de série para login

🔹 Step

Selecione GATE

Clique em Login para acessar o painel.

🔄 Testando o sistema (STEP + GATE em tempo real)

Para testar corretamente o funcionamento do sistema e visualizar as confirmações em tempo real, siga o procedimento abaixo:

Abra duas abas ou janelas do navegador

Na primeira aba:

Faça login como GATE

Matrícula: 222222

Step: GATE

Na segunda aba:

Faça login como STEP

Utilize uma matrícula de operador (ex: 111220)

Informe um número de série válido

Selecione um Step

📌 Dessa forma, será possível:

Confirmar Steps na aba de operação

Visualizar imediatamente as confirmações no painel GATE

Acompanhar o dashboard sendo atualizado em tempo real

