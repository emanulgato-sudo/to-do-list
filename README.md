# 📋 Meu Projeto To-Do List

Este é um aplicativo simples e intuitivo de Lista de Tarefas (*To-Do List*) desenvolvido com o framework **Kivy**, que permite a criação de aplicativos multiplataforma.

O projeto utiliza o formato **JSON** para persistir os dados da lista de tarefas, garantindo que suas tarefas sejam salvas mesmo após fechar o aplicativo.

## ✨ Funcionalidades

* **Adicionar Tarefa:** Insira novas tarefas na sua lista.
* **Visualizar Tarefas:** Exibe todas as tarefas pendentes.
* **Marcar como Concluída:** Opção para marcar tarefas como concluídas (e possivelmente removê-las ou movê-las para uma lista separada).
* **Persistência de Dados:** As tarefas são salvas automaticamente em um arquivo JSON local.

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Kivy:** Framework Python para desenvolvimento de interfaces de usuário multiplataforma.
* **JSON:** Formato de arquivo para armazenamento e recuperação dos dados da lista de tarefas.

## 🚀 Instalação e Execução

Siga os passos abaixo para configurar e executar o projeto em sua máquina.

### Pré-requisitos

Você precisa ter o **Python 3** instalado em seu sistema.

### Passo 1: Clonar o Repositório

Abra o seu terminal ou prompt de comando e clone o projeto:

```bash
git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)
cd SEU_REPOSITORIO

python3 -m venv venv
source venv/bin/activate

python -m venv venv
.\venv\Scripts\activate

pip install kivy
python main.py

.
├── main.py             # Lógica principal do aplicativo Kivy
├── todo.kv             # (Opcional) Arquivo Kivy Language para design da UI
├── data.json           # Arquivo onde as tarefas são persistidas
└── README.md
{
    "tarefa_1": {
        "titulo": "Comprar leite",
        "concluida": false
    },
    "tarefa_2": {
        "titulo": "Enviar e-mail",
        "concluida": true
    }
}

**Instruções Adicionais:**

1.  **`SEU_USUARIO` e `SEU_REPOSITORIO`:** Lembre-se de substituir esses placeholders no comando `git clone` pelo seu nome de usuário e o nome real do seu repositório no GitHub.
2.  **`todo.kv` e `main.py`:** Ajuste a descrição da estrutura do projeto se você tiver nomes de arquivos diferentes (ex: `app.py` em vez de `main.py`).
3.  **`data.json`:** O exemplo do formato JSON é uma sugestão. Se você estiver usando o `kivy.storage.jsonstore`, a estrutura exata do JSON será gerenciada pela biblioteca.
4.  **Licença:** Adicione um arquivo `LICENSE` correspondente à licença MIT (ou outra de sua preferência) no seu repositório.
