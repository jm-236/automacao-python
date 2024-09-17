# Automação de Login e Registro de Produtos
Este projeto é um script em Python que automatiza o processo de login em um sistema da empresa e o registro de produtos utilizando a biblioteca `pyautogui`. O script simula ações de teclado e mouse para realizar essas tarefas de forma automática.

## Pré-requisitos
* Python 3.x
* Biblioteca `pyautogui`
* Biblioteca `pandas`
* Navegador Opera instalado
## Instalação
Clone este repositório:
```Powershell
git clone https://github.com/seu-usuario/automacao-python.git
```
Navegue até o diretório do projeto:
```powershell
cd automacao-python
```
Instale as dependências necessárias:
```powershell
pip install pyautogui pandas
```

## Uso
1. Abra o arquivo main.py e ajuste as coordenadas de clique e os campos de login conforme necessário.
2. Certifique-se de que o navegador Opera está instalado e configurado no seu sistema.
3. Execute o script:
```powershell
python main.py
```

## Funcionamento
O script realiza as seguintes etapas:

1. Abre o navegador Opera e navega até a página de login do sistema da empresa.
2. Realiza o login utilizando as credenciais fornecidas.
3. Lê um arquivo CSV contendo os dados dos produtos a serem registrados.
4. Preenche os campos do formulário de registro de produtos e submete o formulário para cada produto no arquivo CSV.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
