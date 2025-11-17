📄 NF Felipet — Sistema de Emissão de Nota Fiscal Eletrônica (NF-e)

Aplicação Ruby on Rails desenvolvida para compor meu portfólio, oferecendo uma interface completa para emissão de Nota Fiscal Eletrônica (NF-e).
O sistema consome uma API própria (também disponível no meu GitHub) responsável por validar, assinar e transmitir NF-e conforme os padrões oficiais da SEFAZ.

🔗 Demonstração online: https://nf-felipet.onrender.com/

🔗 API utilizada: https://api-nfe-felipet.onrender.com/

🚀 Funcionalidades

🔐 Autenticação de usuários (Devise)

🧾 Cadastro completo de Notas Fiscais

👥 Gestão de clientes

📦 Gestão de produtos

🔑 Upload e gerenciamento de certificados digitais (.pfx)

🔗 Integração direta com a API de NF-e

📤 Envio, consulta e retorno completo da nota

📊 Dashboard com resumo das emissões

🖥️ Interface limpa e responsiva (Bootstrap)

🧱 Tecnologias Utilizadas

Ruby 3.x

Rails 7.x

PostgreSQL

Devise (autenticação)

Bootstrap 5

Turbo / Hotwire

Render (deploy)

📎 Como Funciona a Integração com a API

O sistema faz requisições para a API própria:

Envia os dados da NF-e (emitente, destinatário, produtos etc.)

A API:

valida o XML,

assina digitalmente,

transmite à SEFAZ,

retorna protocolo, status e mensagens.

O sistema exibe os retornos em tela de forma clara para o usuário final.
