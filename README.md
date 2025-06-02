# 🎷 Transcritor de Áudio com Whisper

Este projeto é um script Python que utiliza o modelo [Whisper](https://github.com/openai/whisper) da OpenAI para transcrever automaticamente arquivos de áudio (.mp3, .wav, etc.) para texto.

## 📦 Requisitos

* Python 3.8 ou superior
* Pip (gerenciador de pacotes)
* Recomendado: Ambiente virtual (venv)

## ⚙️ Instalação

1. Crie e ative um ambiente virtual:

```bash
# No Windows
python -m venv .venv
.venv\Scripts\activate
```

2. Instale as dependências:

```bash
pip install -U openai-whisper
```

> Obs: O Whisper instala automaticamente o PyTorch. Se houver erro com torch, instale manualmente:
> `pip install torch`

## 🚀 Como usar

Execute o script principal:

```bash
python Scriptuni07.py
```

Você verá a mensagem:

```
📁 Digite o caminho do arquivo de áudio (.mp3 ou .wav):
```

Cole o caminho completo do arquivo de áudio. Exemplo:

```
C:\Users\seu-usuario\Downloads\Gravação.mp3
```

O modelo será carregado e o áudio transcrito.

## 💡 Exemplo de uso

```
📁 Digite o caminho do arquivo de áudio (.mp3 ou .wav): C:\Users\lazim\Downloads\Gravação.mp3
🔊 Carregando modelo Whisper e transcrevendo o áudio...
📝 Transcrição:
Olá, este é um teste de transcrição automática usando o Whisper.
```


