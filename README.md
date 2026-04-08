# Template de E-mail: Entrega de TCLE e TLE 🦷

Este repositório contém o código-fonte de um template de e-mail em HTML desenvolvido para o projeto de Iniciação Científica da **Estácio (Recife)**. O projeto estuda a relação entre a *Maloclusão Dentária e Hábitos Deletérios em Crianças e Adolescentes*.

O objetivo principal deste e-mail transacional é entregar de forma clara, amigável e segura os links para download do **TCLE** (Termo de Consentimento Livre e Esclarecido) e **TLE** (Termo de Assentimento Livre e Esclarecido) aos voluntários da pesquisa.

---

## 🎯 Objetivo
Facilitar a comunicação com os participantes da pesquisa, enviando os termos de consentimento necessários junto com uma breve dica de saúde bucal, agregando valor à interação.

## 🛠️ Tecnologias e Boas Práticas Utilizadas
Desenvolver e-mails não é como desenvolver para a web convencional. Este template foi codificado visando a máxima compatibilidade com os principais provedores de e-mail (Gmail, Outlook, Apple Mail, etc.).

*   **Estrutura em Tabelas (`<table>`):** Layout construído inteiramente com tabelas aninhadas para evitar quebras de layout em clientes baseados no motor do Microsoft Word (como o Outlook).
*   **CSS Inline:** Todo o estilo crítico foi aplicado diretamente nas tags via atributo `style`.
*   **Design Responsivo:** Utilização de *Media Queries* básicas para garantir uma boa leitura em dispositivos móveis (telas menores que 620px).
*   **Espaçamento Estrutural:** Uso de colunas de tabela vazias (ex: `<td width="20">&nbsp;</td>`) em vez de *margins* para separar botões lateralmente, garantindo suporte em 100% dos clientes.
*   **Web Fonts:** Integração com as fontes *Plus Jakarta Sans* e *Manrope* via Google Fonts, com *fallbacks* seguros (Georgia, Arial, sans-serif) caso o cliente de e-mail do usuário bloqueie fontes externas.

---

## ⚙️ Como Utilizar (Variáveis Dinâmicas)
O código HTML está preparado com marcações para substituição dinâmica de dados por meio da sua ferramenta de envio de e-mails ou backend.

Procure pelas seguintes variáveis no código e substitua-as no momento do disparo:

*   `{{nome}}` - O nome do voluntário ou responsável (Ex: *João*).
*   `{{link_tcle}}` - A URL (link absoluto) para o download do arquivo PDF do TCLE.
*   `{{link_tle}}` - A URL (link absoluto) para o download do arquivo PDF do TLE.

---

## 👥 Equipe da Pesquisa
*   **Pesquisadora e Desenvolvedora:** Marya Eduarda (Estudante de Odontologia / Iniciação Científica)
*   **Coordenadora:** Dra. Mariana Coutinho
*   **Instituição:** Estácio - Recife, PE

---
*© 2026 Estácio Do Recife. Todos direitos reservados.*
