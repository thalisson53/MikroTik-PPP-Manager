🚀 MikroTik PPP Manager
Aplicação web portátil (Flask + routeros_api) para gerenciar PPP secrets e profiles em roteadores MikroTik. Interface moderna para ISPs brasileiros.

✨ Funcionalidades
✅ Conexão MikroTik via API (host/user/pass)

✅ Abas: PPP Secrets (add/listar/remover users) e Profiles

✅ Rate-limits, pools IP, DNS customizáveis

✅ UI escura responsiva com AJAX real-time

✅ .exe standalone (PyInstaller, Windows/Linux)

🔐 Licença 30 dias com validação automática

🚀 Instalação Rápida
📥 Baixe MikroTikPPP_Manager.exe

⚡ Execute → Configure MikroTik (IP/usuário/senha)

🌐 Acesse http://localhost:5050

📋 Requisitos MikroTik
Versão mínima: RouterOS v6.43 (API plaintext=True); v7+ recomendado.
​

Licença: Nível 4+ (PPPoE/PPTP/L2TP full).
​

Serviços: /ip service enable api (porta 8728 TCP); SSL opcional (8729).
​

⚙️ Configuração Router
Cole no terminal:

text
/ip service set api address=0.0.0.0/0 port=8728 disabled=no
/ip firewall filter add chain=input protocol=tcp dst-port=8728 action=accept place-before=0
Credenciais com policy read/write em /ppp.

💻 Hardware Recomendado
Qualquer MikroTik com 64+ MB RAM (v7).

🏆 Testados: RB4011, hEX S, CHR VM.

❌ Evite: <64 MB RAM ou MIPS antigo.

<img width="1439" height="899" alt="MikroTikPPP_Manager" src="https://github.com/user-attachments/assets/d1e42397-f85b-4d8c-9f38-afa777c1e8de" />

​<img width="1439" height="897" alt="Screenshot_3" src="https://github.com/user-attachments/assets/9be32a2d-7ad5-4a2a-a5d6-2d5e1a878e9c" />

<img width="1439" height="897" alt="Screenshot_2" src="https://github.com/user-attachments/assets/dacdce5f-7e43-43e7-a1dc-5ad84dcd027d" />

<img width="1439" height="895" alt="Screenshot_1" src="https://github.com/user-attachments/assets/a869d129-5785-469c-97e5-9c92bf478366" />

