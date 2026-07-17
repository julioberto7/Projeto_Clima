Observatório do Clima — Currais Novos

Projeto de 3 páginas HTML/CSS interligadas: Painel, Boletins e séries históricas e Alerta de baixa umidade, sobre o clima semiárido da região do Seridó, Rio Grande do Norte.


O que foi feito com Bootstrap x o que é autoral

O projeto é majoritariamente CSS autoral (Flexbox, Grid, variáveis CSS,
tipografia, cores e todo o layout das 3 páginas foram escritos do zero, sem
framework). O Bootstrap é usado em uma única parte, isolada: os campos e
o botão de envio do formulário "Receber alertas", na página alerta/index.html.

Usa classes do Bootstrap:


.form-control — campos de texto e e-mail
.form-select — o select de localidade
.form-check, .form-check-input, .form-check-label — checkboxes e radios
.btn, .btn-primary, .w-100 — botão de envio
além dos icones do site


Continua autoral:


Toda a estrutura visual do cartão (.preferencias-card), o fieldset/legend,
o espaçamento entre campos (.campo-form) e a cor de foco/seleção (sobrescrita
no final de style-alerta.css para usar a paleta do projeto em vez do azul
padrão do Bootstrap).
As outras 2 páginas inteiras (painel e boletins) e o resto da página de alerta.


Por que só ali: o formulário é o componente com mais estados nativos do
navegador para lidar (validação, foco, tipos de campo) — usar o Bootstrap
nessa parte evita reescrever do zero um comportamento que o framework já
resolve bem, enquanto o resto do projeto continua demonstrando CSS autoral
(que é o objetivo principal da disciplina).

Utilizamos I.A para o auxílio no gráfico

links utilizados: 

orientações do Ministério da Saúde → https://www.gov.br/saude/pt-br

Instituto Nacional de Meteorologia → https://portal.inmet.gov.br/


