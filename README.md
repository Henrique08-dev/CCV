📋 Sobre o Projeto

O **Circuito Campinense de Vôlei de Praia** é uma plataforma web completa desenvolvida para automatizar e modernizar a gestão de torneios de vôlei de praia. A aplicação oferece soluções tanto para participantes quanto para administradores, proporcionando uma experiência integrada desde a inscrição até a divulgação dos resultados.

🎯 Objetivos

- **Automatizar o processo de inscrições** com integração de pagamentos via PIX
- **Fornecer transparência** através de rankings e resultados em tempo real
- **Facilitar a gestão** administrativa dos torneios
- **Oferecer acompanhamento em tempo real** de vagas e status de pagamento
- **Criar uma plataforma centralizada** para todas as etapas do circuito

👥 Públicos e Funcionalidades

🏐 Área Pública (Participantes)
- **Sistema de inscrição automatizado** com pagamento via PIX
- **Controle de vagas em tempo real** com fechamento automático
- **Visualização do ranking** com filtros por etapa e categoria
- **Galeria de fotos** com carrossel de todas as etapas
- **Informações de contato** direto via WhatsApp e email
- **Acompanhamento de tabelas** e resultados em tempo real
- **Status de pagamento** e lista de times inscritos

👨‍💼 Área Administrativa (Protegida)
- **Sistema de convite por email** para novos administradores
- **Gestão completa do ranking** com pontuação individualizada
- **Criação e edição de tabelas** e resultados em tempo real
- **Controle de inscrições** com status de pagamento
- **Gerenciamento de usuários** administrativos
- **Informações detalhadas** das duplas inscritas

🛠️ Tecnologias Utilizadas

Backend
- **Node.js** com Express.js para API RESTful
- **MongoDB** com Mongoose para persistência de dados
- **JWT** para autenticação segura
- **Bcrypt** para criptografia de senhas
- **PagarMe** para processamento de pagamentos PIX
- **QRCode** para geração de códigos PIX
- **Twilio** para integração com WhatsApp
- **SendGrid** para envio de emails transacionais
- **Sharp** para processamento de imagens
- **FS-extra** para manipulação de arquivos

Frontend
- **React** 18.3.1 com hooks e functional components
- **React Router DOM** v6 para navegação
- **Bootstrap** e **React Bootstrap** para UI responsiva
- **Fetch** para consumo de API
- **React Slick** e **Slick Carousel** para galeria de fotos
- **React Scroll** para navegação suave
- **PagarMe** para integração frontend de pagamentos
- **Twilio** para integração com WhatsApp (A empresa optou por adicionar manualmente os integrantes nos grupos de WhatsApp, visando cortar gastos da aplicação já que o fluxo de pessoas não é grande)

Ferramentas de Desenvolvimento
- **Vite** para build e desenvolvimento rápido
- **ESLint** para qualidade do código
- **Nodemon** para auto-reload no desenvolvimento

💰 Sistema de Pagamentos PIX

- **Integração completa com PagarMe** (A empresa optou por usar apenas a geração do BACEN e confirmação do pagamento via anexação do comprovante)
- **Geração de QR Code** padrão BACEN
- **Cópia e cola** do código PIX
- **Webhooks** para confirmação automática de pagamentos (A empresa optou por usar apenas a geração do BACEN e confirmação do pagamento via anexação do comprovante)
- **Atualização em tempo real** do status de pagamento

📊 Funcionalidades Principais

🎯 Sistema de Inscrições
- **Formulário de inscrição** com dados completos da dupla
- **Pagamento integrado** via PIX
- **Controle automático de vagas**
- **Confirmação por email** após inscrição
- **Status de pagamento** atualizado em tempo real

🏆 Sistema de Ranking
- **Pontuação individual** por atleta
- **Cálculo automático** da pontuação da dupla
- **Filtros por etapa** e categoria
- **Classificação transparente** e pública

📋 Gestão de Torneios
- **Criação de chaves** e tabelas
- **Edição de resultados** em tempo real
- **Divisão em fases** (grupos e fase final)
- **Visualização pública** dos resultados

📸 Galeria de Fotos
- **Carrossel responsivo** de imagens
- **Organização por etapas**
- **Upload e gestão** de fotos
- **Interface intuitiva** para visualização

📞 Sistema de Contato
- **Integração com WhatsApp**
- **Formulário de email** via SendGrid
- **Comunicação direta** com organização

🔐 Sistema de Autenticação Administrativa

- **Convite por email** para novos administradores
- **Senha padrão** com obrigatoriedade de alteração
- **Recuperação de senha** segura
- **Controle de acesso** baseado em roles
- **Tokens JWT** para sessões seguras

🚀 Funcionalidades Técnicas

- **Websockets** para atualizações em tempo real
- **Upload de imagens** otimizado com Sharp
- **Validação de dados** em frontend e backend
- **Responsividade** completa para mobile e desktop
- **SEO optimizado** para páginas públicas
- **Performance optimizada** com lazy loading

🔒 Segurança

- **Criptografia** de senhas com bcrypt
- **Proteção contra XSS** e injection
- **Validação de inputs** rigorosa
- **Tokens JWT** com expiration
- **CORS configurado** adequadamente

---

**Circuito Campinense de Vôlei de Praia** - Modernizando a gestão de torneios esportivos 🏐✨
**Para acessar o site:** https://circuitocampinense.netlify.app/ (Devido ao baixo fluxo de usuários, a empresa optou por não utilizar servidores backend próprios)
