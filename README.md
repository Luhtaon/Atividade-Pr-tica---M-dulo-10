Modificações no Código
ListarTarefa.jsx
Adição dos estados 'historicoTarefas' e 'mostrarHistorico' para controlar o histórico de tarefas.
Adição do botão "Mostrar Histórico" para alternar a exibição do histórico de tarefas.
Criação de um segundo bloco de tabela para exibir o histórico de tarefas quando 'mostrarHistorico' é true.
Modificação da lógica de exclusão para mover tarefas concluídas para o histórico.
Criação do AlertDialog.jsx
Cria um novo componente 'AlertDialog' para exibir um diálogo de confirmação.
Recebe as props 'open', 'handleClose', 'handleConfirm', 'title', e 'description'.
Utiliza o componente 'Dialog' do Material-UI para exibir o diálogo.
Exibe um título e uma descrição no corpo do diálogo.
Adiciona botões de ação para confirmar ou cancelar a operação.
Adição do Componente AlertDialog no ListarTarefa.jsx
Adição do componente 'AlertDialog' para mostrar um diálogo de confirmação antes de excluir uma tarefa.
Implementação do componente 'AlertDialog' para exibir um diálogo de confirmação ao tentar excluir uma tarefa.
Implementação a lógica para abrir e fechar o diálogo de confirmação.
Modificações dos estilos
App.css
Adiciona classes .table-row-even e .table-row-odd para estilizar as linhas da tabela alternadamente.
