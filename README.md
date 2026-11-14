# IPTV Lite - Gerenciador Mobile Web (GitHub Pages)

Este repositório contém o painel web mobile para gerenciar o **IPTV Lite** na Smart TV Samsung (Tizen 5.5).

Página ativa: **[https://manoelvrsilva.github.io/iptv-remote/](https://manoelvrsilva.github.io/iptv-remote/)**

---

## 📱 Recursos
- **Configuração do Servidor:** Editar URL Xtream Codes, servidores de backup (failover), Usuário e Senha com segurança.
- **Gerenciamento de Categorias:** Ocultar ou exibir categorias com busca e botão de selecionar/desmarcar tudo.
- **Backup & Restauração Versionada:** Exportar e importar configurações completas (`.json`) com fusão tolerante (Deep Merge) para futuras atualizações do app.

---

## 🔒 Segurança e Conectividade
- **Zero dados salvos na nuvem:** Credenciais e listas nunca são armazenadas em servidores externos.
- **Criptografia Ponta a Ponta (E2EE):** Todas as mensagens entre TV e celular trafegam cifradas e autenticadas (Encrypt-then-MAC com IV aleatório de 128 bits, tag MAC de 128 bits e chave secreta de 24 caracteres embutida no QR Code).
- **Conexão Instantânea (HTTPS / SSE):** Funciona perfeitamente entre 4G/5G e Wi-Fi sem restrições de NAT ou roteador.
- **Proteção por PIN e Anti-Força Bruta:** A TV gera um PIN dinâmico de 4 dígitos por sessão e rotaciona automaticamente sessão/PIN/chave após 5 tentativas inválidas.
