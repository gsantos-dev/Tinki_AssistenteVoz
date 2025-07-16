# 🤖 Tinki – Assistente de Voz com IA (LangChain + Whisper + OpenAI)

Projeto pessoal que desenvolve um assistente de voz inteligente e responsivo, capaz de escutar comandos do usuário, interpretar com IA e responder em áudio de forma natural.

---

## ⚙️ Tecnologias Utilizadas

- Python 3.10+
- [LangChain](https://www.langchain.com/)
- [OpenAI API (Chat + TTS)](https://platform.openai.com/)
- [Whisper](https://github.com/openai/whisper)
- Pandas
- Pynput
- SoundDevice
- SoundFile

---

## 🎯 Funcionalidades

- ✅ Ativação por tecla (Ctrl)
- 🎙️ Grava e transcreve sua voz com Whisper
- 📊 Interpreta comandos via agente LangChain com DataFrame Pandas
- 🔊 Gera resposta por voz usando TTS da OpenAI
- 💡 Nome do assistente: **Tinki**

---

## 📁 Estrutura do Projeto
Tinki_AssistenteVoz/
├── .env # Sua chave da API OpenAI (não subir no GitHub)
├── df_rent.csv # Base de dados usada pelo agente Pandas
├── Project_Agente.py # Script principal com a classe TalkingLLM
├── requirements.txt # Dependências do projeto


---

## 🚀 Como Executar o Projeto

### 1. Clone o repositório:

git clone https://github.com/gsantos-dev/Tinki_AssistenteVoz.git
cd Tinki_AssistenteVoz

### 2. Instale as dependencias
pip install -r requirements.txt

### 3. Crie um arquivo chamado .env na raiz do projeto com sua chave OpenAI



⚠️ Observações
Pressione Ctrl para iniciar/parar a gravação.

A transcrição é feita localmente com Whisper.

O agente responde com base no DataFrame df_rent.csv.

O áudio é gerado com a voz Alloy da OpenAI.

É necessário estar com microfone ativado e saída de som configurada.




