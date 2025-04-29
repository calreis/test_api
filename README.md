# API LISTA DE TAREFAS
✅ API de Tarefas Uma API simples para gerenciamento de tarefas, feita com Flask. Permite criar, listar, atualizar e excluir tarefas.


📚 Endpoints

Método | Rota | Descrição

GET | /tarefas | Lista todas as tarefas

POST | /tarefas | Cria uma nova tarefa

PUT | /tarefas/<id> | Atualiza a descrição de uma tarefa

DELETE | /tarefas/<id> | Exclui uma tarefa específica

🧱 Estrutura da Tarefa

![image](https://github.com/user-attachments/assets/1970294c-5610-4431-b191-38d51fc58c97)

id (integer): identificador único da tarefa.

descricao (string): descrição da tarefa.

📥 Exemplos de Uso

1. Listar todas as tarefas
Requisição:

![image](https://github.com/user-attachments/assets/7657a5cc-4448-4b15-83be-6c6d12830569)

Resposta:

![image](https://github.com/user-attachments/assets/733d1aaa-d41a-441a-acb2-5ff02035e86b)

2. Criar uma nova tarefa
Requisição:

![image](https://github.com/user-attachments/assets/eadcb465-4063-478c-b482-47b65e7fbdb4)

Resposta:

![image](https://github.com/user-attachments/assets/cd0cf271-362c-4c2c-8f86-f8d8a35b305f)

2. Criar uma nova tarefa
Requisição:

![image](https://github.com/user-attachments/assets/c155652c-42ac-448b-9d6a-4364012e5af3)

Resposta:

![image](https://github.com/user-attachments/assets/8b9f55fa-d56c-40f3-831d-409987a305a8)

3. Atualizar uma tarefa existente
Requisição:
![image](https://github.com/user-attachments/assets/c9a9bfa5-243d-48d4-8161-6f12ce400535)

Resposta:

![image](https://github.com/user-attachments/assets/30b1eeec-8900-4767-8390-e51209eba68d)

4. Excluir uma tarefa
Requisição:

![image](https://github.com/user-attachments/assets/5bc0dc3f-a91e-44cc-8882-04ebbed06bf9)

Resposta:

![image](https://github.com/user-attachments/assets/a4e4d0a8-0d71-447b-a271-15b76938e3cc)

🚀 Como Rodar Localmente

1. Clone o repositório:

![{2398BE59-CF60-4874-8F47-3163F9E2BAB0}](https://github.com/user-attachments/assets/f39ec9e9-683f-4d09-b764-3d928ec3e406)

2. Instale as dependências:

![image](https://github.com/user-attachments/assets/72d97616-63bf-40d0-b223-64bae49e7ea2)

3. Execute o projeto:

![image](https://github.com/user-attachments/assets/a8ff7267-8287-4d16-bb73-a3f6b075f868)

A aplicação estará disponível em:
ex: http://localhost:5000

🛠 Tecnologias Utilizadas
Python 3.11+
Flask

🗒️ Observações:

As tarefas são armazenadas na memória enquanto o servidor está ativo.

Ao reiniciar o servidor, todas as tarefas serão apagadas.

Para persistência real, recomenda-se integrar com um banco de dados (como SQLite, PostgreSQL, etc).

📄 Licença
Este projeto está sob a licença MIT.
