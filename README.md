# 🐼 Mini-curso de Pandas 📊

```
 ____                 _
|  _ \ __ _ _ __   __| | __ _ ___
| |_) / _` | '_ \ / _` |/ _` / __|
|  __/ (_| | | | | (_| | (_| \__ \
|_|   \__,_|_| |_|\__,_|\__,_|___/

        🐍 Python  +  🐼 pandas  +  📊 Matplotlib
```

**Aprenda a manipular e visualizar dados com Python**

`🐍 Python 3.10+` · `🐼 pandas` · `📊 Matplotlib`

---

## 🗺️ Roadmap da configuração

```
  🐍 Python        📥 Clonar        📦 Criar         ⚡ Ativar
  instalado   ──▶  repositório ──▶  .venv      ──▶  .venv
     [1]              [2]             [3]             [4]
                                                       │
                                                       ▼
  🎉 Pronto!  ◀──  ✅ Testar   ◀──  🐼📊 Instalar ◀──  🔧 Atualizar
  para a aula      instalação       pandas +        pip
                      [7]           matplotlib       [5]
                                       [6]
```

| Etapa | O que fazemos | Status |
| :---: | --- | :---: |
| 1️⃣ | 🐍 Verificar o Python | ⬜ |
| 2️⃣ | 📥 Clonar o repositório | ⬜ |
| 3️⃣ | 📦 Criar o ambiente virtual `.venv` | ⬜ |
| 4️⃣ | ⚡ Ativar o ambiente virtual | ⬜ |
| 5️⃣ | 🔧 Atualizar o `pip` | ⬜ |
| 6️⃣ | 🐼 Instalar pandas e Matplotlib | ⬜ |
| 7️⃣ | ✅ Verificar a instalação | ⬜ |

---

## 🧰 Pré-requisitos

- 🐍 **Python 3.10 ou mais recente**
- 🌿 **Git** (para clonar o repositório)
- 💻 Um terminal (Terminal no Linux/macOS, PowerShell no Windows)
- 📝 Um editor de código (recomendado: [VS Code](https://code.visualstudio.com/))

> 🖥️ Os comandos aparecem separados por sistema:
> 🐧 **Linux** · 🍎 **macOS** · 🪟 **Windows**

---

## 1️⃣ 🐍 Verificar se o Python está instalado

🐧🍎 **Linux / macOS**

```bash
python3 --version
```

🪟 **Windows (PowerShell)**

```powershell
python --version
```

✔️ A saída deve ser algo como `Python 3.12.x`.

❌ **Comando não encontrado?** Instale o Python:

- 🪟 **Windows:** baixe em [python.org/downloads](https://www.python.org/downloads/) e, na instalação, **marque a opção "Add Python to PATH"**.
- 🍎 **macOS:** `brew install python` (com [Homebrew](https://brew.sh/)) ou o instalador do python.org.
- 🐧 **Linux (Debian/Ubuntu):** `sudo apt install python3 python3-venv python3-pip`
- 🐧 **Linux (Fedora):** `sudo dnf install python3 python3-pip`

---

## 2️⃣ 📥 Clonar o repositório

```bash
git clone <URL-DO-REPOSITORIO>
cd mini-curso-pandas
```

> 💡 Substitua `<URL-DO-REPOSITORIO>` pelo link do repositório.

---

## 3️⃣ 📦 Criar o ambiente virtual (`.venv`)

> 🤔 **Por que usar um ambiente virtual?**
> Ele funciona como uma "caixinha" 📦 só para este projeto: as bibliotecas instaladas aqui não se misturam com as do resto do computador.

```
  💻 Seu computador
  ┌─────────────────────────────────────────┐
  │  🐍 Python do sistema                   │
  │                                         │
  │   ┌─────────────────────────────────┐   │
  │   │ 📦 .venv (mini-curso-pandas)    │   │
  │   │   🐼 pandas                     │   │
  │   │   📊 matplotlib                 │   │
  │   │   🔢 numpy                      │   │
  │   └─────────────────────────────────┘   │
  └─────────────────────────────────────────┘
```

🐧🍎 **Linux / macOS**

```bash
python3 -m venv .venv
```

🪟 **Windows (PowerShell)**

```powershell
python -m venv .venv
```

✔️ Uma pasta chamada `.venv` será criada dentro do projeto.

---

## 4️⃣ ⚡ Ativar o ambiente virtual

🐧🍎 **Linux / macOS**

```bash
source .venv/bin/activate
```

🪟 **Windows (PowerShell)**

```powershell
.venv\Scripts\Activate.ps1
```

🪟 **Windows (Prompt de Comando / cmd)**

```cmd
.venv\Scripts\activate.bat
```

✔️ Com o ambiente ativo, `(.venv)` aparece no início da linha do terminal:

```
(.venv) usuario@maquina:~/mini-curso-pandas$
```

> ⚠️ **Erro no PowerShell** dizendo que a execução de scripts está desabilitada?
> Rode o comando abaixo **uma vez** e tente ativar novamente:
>
> ```powershell
> Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
> ```

---

## 5️⃣ 🔧 Atualizar o `pip`

Com o ambiente ativado (em qualquer sistema):

```bash
python -m pip install --upgrade pip
```

> 💡 Dentro do `.venv`, o comando `python` já aponta para o Python do ambiente, inclusive no Linux/macOS.

---

## 6️⃣ 🐼📊 Instalar o pandas e o Matplotlib

```bash
pip install pandas matplotlib
```

| Biblioteca | Para que serve |
| --- | --- |
| 🐼 **pandas** | Ler, limpar, filtrar e analisar tabelas de dados |
| 📊 **Matplotlib** | Criar gráficos e visualizações |
| 🔢 **NumPy** | Cálculos numéricos (instalado automaticamente junto com o pandas) |

---

## 7️⃣ ✅ Verificar a instalação

```bash
python -c "import pandas as pd, matplotlib; print('pandas', pd.__version__); print('matplotlib', matplotlib.__version__)"
```

✔️ Saída esperada (as versões podem variar):

```
pandas 2.x.x
matplotlib 3.x.x
```

```
   🎉🎉🎉  TUDO PRONTO!  🎉🎉🎉

      ／l、
    （ﾟ､ ｡ ７    Ambiente configurado.
      l  ~ヽ      Bora pra aula de pandas! 🐼
      じしf_,)ノ
```

---

## 🧠 Cola rápida (cheat sheet)

| 🎯 Ação | ⌨️ Comando |
| --- | --- |
| 🔌 Desativar o ambiente virtual | `deactivate` |
| 📋 Ver os pacotes instalados | `pip list` |
| 💾 Salvar as dependências em um arquivo | `pip freeze > requirements.txt` |
| 📥 Instalar a partir do arquivo | `pip install -r requirements.txt` |

## 💡 Dicas úteis

- 🔁 **Sempre ative o `.venv`** (etapa 4️⃣) ao abrir um novo terminal para trabalhar no projeto.
- 🧩 **No VS Code**, use `Ctrl+Shift+P` → *Python: Select Interpreter* e escolha o interpretador que está dentro de `.venv`.
- 🚫 A pasta `.venv` **não deve ser enviada ao Git**. Adicione-a ao `.gitignore`:

  ```bash
  echo ".venv/" >> .gitignore
  ```

---

*Feito com 💙 e 🐼 para o Mini-curso de Pandas*
