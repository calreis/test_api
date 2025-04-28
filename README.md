# test_api
✅ API de Tarefas Uma API simples para gerenciamento de tarefas, feita com Flask. Permite criar, listar, atualizar e excluir tarefas.

Método | Rota | Descrição

GET | /tarefas | Lista todas as tarefas
POST | /tarefas | Cria uma nova tarefa
PUT | /tarefas/<id> | Atualiza a descrição de uma tarefa
DELETE | /tarefas/<id> | Exclui uma tarefa específica

🧱 Estrutura da Tarefa
json
Copiar
Editar
{
  "id": 1,
  "descricao": "Estudar Flask"
}
id (integer): identificador único da tarefa.

descricao (string): descrição da tarefa.

🛠 Tecnologias Utilizadas
Python 3.11+

Flask
