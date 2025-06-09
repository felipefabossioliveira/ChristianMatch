# App de Relacionamentos - Documentação de Telas (MVP)

> Foco em conexões genuínas com valores tradicionais. Relacionamentos sérios, seguros e respeitosos.

---

## 1. Tela de Login/Registro (MVP)

📌 **Objetivo:** Autenticar o usuário com segurança e flexibilidade.

🔹 **Componentes:**
- Login com e-mail
- Login com número de celular (SMS)
- Registro com nome completo, e-mail, celular, senha
- Botão “Entrar com Google” e “Entrar com Apple” (futuro)
- Validação de número com código via SMS
- Recuperação de senha via e-mail/SMS

---

## 2. Verificação em Duas Etapas (MFA)

📌 **Objetivo:** Aumentar a segurança da conta.

🔹 **Componentes:**
- Envio de código SMS para segundo fator
- Tela de digitação de código
- Opcionais: configurar dispositivo confiável

---

## 3. Onboarding Cristão (Cadastro de Perfil)

📌 **Objetivo:** Coletar informações fundamentais com foco em valores cristãos.

🔹 **Componentes:**
- Foto de perfil
- Denominação religiosa (lista com opção “Outro”)
- Frequência na igreja
- Versículo favorito (texto livre)
- Intenção: namoro, casamento, amizade
- Biografia curta
- Preferência de idade e localização
- Hobbies e interesses

---

## 4. Tela de Exploração de Perfis

📌 **Objetivo:** Apresentar pessoas compatíveis sem usar curtidas rasas.

🔹 **Nova Lógica de Match:**
- Respostas cruzadas: o sistema recomenda pessoas com base nas respostas do onboarding
- Possibilidade de “Iniciar Conversa” com limite diário (ex: 3 novas por dia)
- Confirmação mútua baseada em interesses/valores (ex: "Ambos priorizam a fé como base do relacionamento")

---

## 5. Chat Seguro

📌 **Objetivo:** Comunicação direta entre os usuários.

🔹 **Componentes:**
- Chat em tempo real
- Botão de “Agendar Videochamada”
- Denunciar usuário/conversa
- Marcar conversa como inapropriada (ativa moderação automática)

---

## 6. Videochamada

📌 **Objetivo:** Conexões mais próximas, seguras e moderadas.

🔹 **Componentes:**
- Chamada por vídeo integrada
- Permitir chamada agendada com alerta
- Permitir chamadas instantâneas (opcional)
- Monitoramento por IA (bloqueio de conteúdo explícito em tempo real)

---

## 7. Moderação de Conteúdo

📌 **Objetivo:** Manter o ambiente seguro e respeitoso.

🔹 **Tipos de Moderação:**
- Texto: IA detecta conteúdo impróprio (palavrões, assédio, conteúdo sexual)
- Imagem/Vídeo: detecção automática de nudez ou violência
- Áudio/Vídeo: análise em tempo real de conteúdo explícito
- Denúncia manual em qualquer conteúdo ou perfil
- Sistema de strikes e banimentos

---

## 8. Descoberta por Localização

📌 **Objetivo:** Encontrar pessoas próximas com mesmos valores.

🔹 **Componentes:**
- Modo “cidade/estado” ou por raio (ex: 50km)
- Preferência ajustável no perfil

---

## 9. Tela de Assinatura Premium

📌 **Objetivo:** Oferecer recursos exclusivos.

🔹 **Funcionalidades Premium sugeridas:**
- Ver quem visitou seu perfil
- Videochamadas ilimitadas
- Acesso a filtros avançados (ex: valores específicos, planos de vida)
- Aumento do limite de conversas diárias
- Destaque no sistema de recomendação

---

## 10. Perfil de Usuário

📌 **Objetivo:** Exibir e permitir edição das informações.

🔹 **Componentes:**
- Foto, bio, versículo
- Campos cristãos (frequência, denominação)
- Configurações de privacidade
- Preferências de busca

---

## 11. Painel Administrativo Web (Admin)

📌 **Objetivo:** Gerenciar o ecossistema do app.

🔹 **Funcionalidades:**
- Moderar denúncias e conteúdos
- Banir usuários
- Ver métricas de uso (ativos, retenção, denúncias)
- Gerenciar planos e pagamentos
- Enviar mensagens ou notificações para usuários

---

## 12. Configurações

📌 **Objetivo:** Personalizar e proteger a experiência do usuário.

🔹 **Componentes:**
- Notificações
- Conta e senha
- Privacidade e segurança
- Suporte e ajuda
- Sair da conta

---

## 13. Sistema de Notificações

📌 **Objetivo:** Engajamento e alertas importantes.

🔹 **Tipos:**
- Mensagens recebidas
- Recomendação de novo perfil
- Lembrete de onboarding incompleto
- Alerta de agendamento de chamada
- Acontecimentos cristãos (ex: culto, live, meditação)

---

# ✝️ Visão Cristã e Ética

- Todos os textos do app terão linguagem respeitosa e acolhedora
- Mensagens motivacionais cristãs podem aparecer como onboarding
- IA para proteger, não vigiar. A moderação será explicada e transparente.

---

# 📌 Próximos passos

- Definir nome do app
- Wireframes das principais telas
- Escolha da stack de desenvolvimento (Flutter? React Native? Swift/Kotlin?)
- Definição do MVP realista para validação com cristãos(as) solteiros(as)
