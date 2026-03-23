# VOX Note - Bot para Reuniões do Discord
![Logo VoxNote](blob:https://web.whatsapp.com/71c4068d-0ad4-48c5-bb2f-bc974609b0ff)


Projeto desenvolvido para a disciplina **Análise de Projetos II** do 4ᵒ semestre do curso de **Análise e Desenvolvimento de Sistemas** da **CEUNSP**.  
O VOX Note é um bot para Discord que captura o áudio de reuniões, transcreve e gera atas resumidas com auxílio de inteligência artificial, facilitando o registro e a consulta de informações importantes.

---

##  Colaboradores
- **Gerente**: Raian Infante Pereira  
- **Scrum Master**: Gabriele Martins  
- **Programador 1**: Enzo Vinicius  
- **Programador 2**: Enzo Guimarães  
- **Analista de Negócios**: Alisson Ryan  
- **Documentador Técnico**: Samuel    
- **Inspetor de Qualidade**: Nicolas Lopes  
- **Analista de Testes**: Igor Lopes  

---

# 📝 VOX Note  
### *Bot para Registro Automatizado de Reuniões no Discord*

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Discord.py](https://img.shields.io/badge/Discord.py-Bot-blueviolet)
![Whisper](https://img.shields.io/badge/OpenAI-Whisper-green)
![MIT License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Ativo-success)

---

## 📌 Sobre
O **VOX Note** é um bot projetado para registrar automaticamente reuniões realizadas no Discord.  
Ele grava áudio, transcreve utilizando **Whisper**, e gera atas padronizadas com auxilio de uma API da **OpenAI**.
---

## 🎯 Objetivos
- Automatizar o registro de reuniões  
- Evitar anotações manuais  
- Aumentar a precisão das atas  
- Facilitar a padronização e controle  
- Integrar IA ao fluxo de documentação  

---

# ⚙️ Requisitos Técnicos

## Software
- Python **3.10+**
- discord.py  
- openai  
- whisper ou faster-whisper  
- aiohttp  
- python-docx  
- Dependências do `requirements.txt`

## Hardware
- CPU Dual-core  
- 4 GB RAM  
- 2 GB livre  
- Internet estável  

---

# 📥 Instalação

## 1. Clone o repositório
~~~bash
git clone https://github.com/usuario/repositorio.git
cd repositorio
~~~

## 2. (Opcional) Crie o ambiente virtual
~~~bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
~~~

## 3. Instale as dependências
~~~bash
pip install -r requirements.txt
~~~

## 4. Configure as variáveis de ambiente
Crie um arquivo **.env**:

~~~env
DISCORD_TOKEN=seu_token
OPENAI_API_KEY=sua_chave
~~~

---

# ▶️ Como Usar

## Inicie o bot
~~~bash
python bot.py
~~~

## Comandos principais (exemplo)
- `!gravar` → Inicia a gravação  
- `!parar` → Finaliza e gera a ata  
- `!ata` → Envia a ata produzida  

---

# 🔄 Fluxo Operacional

1. Bot entra no canal  
2. Captura áudio  
3. Trata e converte  
4. Transcreve com Whisper  
5. Resume com OpenAI  
6. Gera a ata  
7. Envia ao usuário  

---

# 🤝 Contribuições
Pull Requests são bem-vindos!

---

# 📩 Contato
Se quiser expandir o projeto ou integrar novas funções, é só chamar 🚀
