# Criando-um-App-de-Lembretes-e-Tarefas-com-Swift
**Criar um aplicativo estilo "To Do List"** é um excelente projeto para quem deseja aprender a desenvolver aplicativos móveis usando **Swift**. Vamos lá!

## Passo 1: Configuração do Projeto
1. Abra o **Xcode** (a IDE oficial da Apple para desenvolvimento iOS).
2. Crie um novo projeto selecionando **"File" > "New" > "Project..."**.
3. Escolha a opção **"App"** e clique em **"Next"**.
4. Preencha os detalhes do projeto, como nome, organização e idioma (Swift).
5. Escolha um local para salvar o projeto e clique em **"Create"**.

## Passo 2: Interface do Usuário (UI)
1. No **Main.storyboard**, arraste um **Table View** para a tela.
2. Adicione um **Navigation Controller** para gerenciar a navegação.
3. Crie uma nova tela para adicionar tarefas (por exemplo, **AddTaskViewController**).
4. Crie uma célula personalizada para exibir as tarefas na lista.

## Passo 3: Modelagem de Dados
1. Crie uma classe chamada **Task** para representar uma tarefa com propriedades como título, descrição e data de conclusão.
2. Crie uma classe chamada **TaskManager** para gerenciar a lista de tarefas (adicionar, remover, atualizar).

## Passo 4: Implementação da Lógica
1. No **AddTaskViewController**, crie uma interface para o usuário inserir os detalhes da tarefa.
2. Ao salvar, crie uma instância de **Task** com os dados inseridos e adicione-a ao **TaskManager**.
3. Na tela principal, exiba a lista de tarefas usando a **Table View** e a célula personalizada.
4. Implemente a lógica para marcar tarefas como concluídas ou excluí-las.

## Passo 5: Teste e Depuração
1. Execute o aplicativo no simulador ou em um dispositivo real.
2. Verifique se a adição e remoção de tarefas estão funcionando corretamente.
3. Use o **Console** para depurar eventuais erros.

## Passo 6: Polimento
1. Adicione ícones e imagens para tornar o aplicativo mais atraente.
2. Melhore a interface do usuário com animações e transições suaves.
3. Teste em diferentes dispositivos e resoluções.

**Lembre-se de consultar a documentação oficial do Swift e do Xcode para obter mais detalhes sobre cada etapa.** 

https://docs.google.com/presentation/d/1D3zjmBY-6aKhT6WSSrHsEFYgUxfLZ-pE/edit?usp=sharing&ouid=105780375946211087074&rtpof=true&sd=true

https://github.com/vergisf/App-ToDoList
