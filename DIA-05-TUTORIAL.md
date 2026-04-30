# 🥷 Mentor404 - Dia 05: Mensagens 100% Anônimas (O Fim do Chip)

Bem-vindo ao **Dia 5 do Kit Anti-Rastreio**! Se no Dia 4 cortamos o Google da sua vida, hoje vamos cortar a sua operadora de celular das suas conversas.

Muita gente acha que baixar o Telegram ou o Signal já é o auge da segurança. O problema? **Eles exigem o seu número de telefone.**

---

## 🎯 O Problema do Número de Celular
Se um aplicativo pede o seu número, ele já sabe quem você é. 
O seu número de celular está atrelado ao seu CPF, ao seu endereço e à sua operadora. Em uma investigação ou num vazamento de dados, o número é a "chave-mestra" que liga o seu perfil anônimo à sua identidade no mundo real.

O Signal é excelente para criptografia, mas **falha no anonimato**. Nós queremos o nível *hardcore*.

---

## 🧅 A Solução: Conheça o Session
Para o **Mentor404**, a escolha técnica definitiva para comunicação é o **Session**.

**Por que o Session é diferente de tudo o que você já usou?**
1. **Zero Número de Telefone:** Você não precisa de chip, e-mail ou nome para criar a conta. O sistema gera um código aleatório (Session ID) e esse é o seu "número".
2. **Rede Descentralizada:** Não existe um servidor central do Session que possa ser hackeado ou desligado por governos. As mensagens pulam por vários computadores pelo mundo (uma rede parecida com o Tor/Onion), escondendo de onde a mensagem saiu e para onde ela vai.
3. **À prova de metadados:** Eles não sabem com quem você fala, nem a hora que você fala, nem o seu IP.

---

## 🛠️ Passo a Passo: Instalando e Usando o Session

Não se assuste com os termos técnicos, usar o Session é tão fácil quanto o WhatsApp.

### Passo 1: Baixar o App
* Você pode baixar na **App Store** (se usar iPhone), na **Google Play**, ou direto no site oficial (getsession.org) para o computador. 
* Procure pelo ícone verde com um "S" branco estilizado.

### Passo 2: Criando sua Identidade (O Session ID)
1. Abra o aplicativo e clique em **Create Session ID** (Criar ID do Session).
2. O aplicativo vai gerar automaticamente uma sequência enorme de letras e números. **Esse é o seu contato.** É isso que você manda para os seus amigos em vez do seu número de celular.
3. Escolha um "Display Name" (Nome de Exibição). Pode ser qualquer apelido, como "Mentor404".

### Passo 3: Salve a sua Vida (A Frase de Recuperação) 🚨
Como você não colocou e-mail nem telefone, não existe "Esqueci minha senha". 
O Session vai te dar uma **Recovery Phrase** (Frase de Recuperação), que é uma lista de palavras aleatórias.
👉 **Se você perder o celular e não tiver essas palavras anotadas, você perde a conta para sempre.** Anote num papel físico e guarde bem.

### Passo 4: Como adicionar alguém?
Em vez de passar o seu número, você vai copiar o seu **Session ID** e mandar para a pessoa, ou mostrar o seu QR Code direto na tela do app. A pessoa cola no aplicativo dela e a conversa começa.

---

## 💻 Para o vídeo do TikTok (Desafio OSINT)
Se você quer ver como um número de celular te entrega de bandeja para hackers ou investigadores, rode o script `rastreio_celular_vs_session.py` que deixamos nesta pasta. Ele simula o que um script de OSINT consegue descobrir só com o seu número, comparado com o Session ID.

*Projeto Mentor404 - A sua identidade não é moeda de troca.*
