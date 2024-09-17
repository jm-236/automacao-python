# Automacao-python
![image](https://github.com/user-attachments/assets/f9a451b1-e273-4b41-8399-fe6286d2e945)


## Resumo
* O código fornecido é um script Python projetado para automatizar o processo de login no sistema de uma empresa, importar um conjunto de dados e registrar produtos usando a biblioteca pyautogui. Esta biblioteca permite que o script simule ações de teclado e mouse, o que é útil para automatizar tarefas repetitivas.

* O projeto foi desenvolvido na imersão de python da Hashtag Produções

## Funcionamento
* O script começa definindo uma URL para a página de login do sistema da empresa e importando as bibliotecas necessárias, incluindo pyautogui para automação e tempo para adicionar atrasos. Ele define um intervalo de pausa de 0,5 segundos entre cada comando pyautogui para garantir que o sistema tenha tempo suficiente para processar cada ação.

* A primeira tarefa principal é abrir o navegador da web e navegar até a página de login. Isso é obtido simulando pressionamentos de tecla para abrir o navegador (neste caso, Opera), inserindo a URL e pressionando Enter. Após uma breve pausa para permitir que a página carregue, o script prossegue para a etapa de login. Ele clica no campo de nome de usuário, insere o endereço de e-mail, navega até o campo de senha usando a tecla Tab, insere a senha e envia o formulário pressionando Enter. Uma pausa mais longa é adicionada aqui para garantir que o processo de login seja concluído.

* Em seguida, o script importa a biblioteca pandas e lê um arquivo CSV chamado "produtos.csv" em um DataFrame chamado tabela. Este DataFrame contém os dados do produto que serão registrados no sistema.

* O script então entra em um loop para iterar sobre cada linha no DataFrame. Para cada produto, ele clica em um local específico na tela para focar no formulário de registro do produto. Em seguida, ele preenche sequencialmente os detalhes do produto, como código, marca, tipo, categoria, preço unitário e custo, escrevendo os valores correspondentes do DataFrame e pressionando a tecla Tab para mover para o próximo campo. Se houver alguma observação (obs) para o produto, ele verifica se o valor não é NaN (Not a Number) e o escreve no formulário, seguido pelo pressionamento de Tab.

* Após preencher todos os campos de um produto, o script envia o formulário pressionando Enter e rola a página para cima para se preparar para a próxima entrada do produto. Esse processo se repete para cada produto no DataFrame, automatizando todo o processo de registro.

* **IMPORTANTE**: O funcionamento do script varia de tela para tela em função da diferença de tamanho entre o monitor no qual ele foi testado e outro monitor de dimensões diferentes.
