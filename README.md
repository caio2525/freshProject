## About The Project
Aplicação CRUD utilizando a seguinte stack de tecnologias:
Front-End: React JS
API: Python Flask
Banco de Dados: MongoDb

Video: https://www.awesomescreenshot.com/video/7194554?key=65ae70b59c408f5bc5373fe2e67ef429

### Built With

* [React.js](https://pt-br.reactjs.org/)
* [Python](https://www.python.org/)
* [Flask](https://flask.palletsprojects.com/)

## Getting Started
Para fazer o projeto rodar localmente na sua máquina siga os passos de instalação a seguir.  

### Backend Setup

1. Clone o repositório Backend e navegue para dentro dele
  ```sh
   git clone https://github.com/caio2525/freshBack.git
   ```
   
2. Crie um ambiente virtual python com a versão 3.8 e o ative
   ```sh
   python3.8 -m venv env
   ```

   ```sh
   source env/bin/activate
   ```

3. Instale as depedências
    ```sh
   pip install -r requirements.txt
   ```
   
4. Inicie o servidor
   ```sh
   python main.py
   ```
Seu servidor deverá estar rodando http://127.0.0.1:5000/

### Frontend Setup
1. Clone o repositório frontEnd e navegue para dentro dele
  ```sh
   git clone https://github.com/caio2525/freshfront.git
   ```

2. Instale as depedências
   ```sh
   yarn install
   ```

3. Inicie a aplicação
    ```sh
   yarn start
   ```

Espere até que a aplicação abra no navegador ou Abra http://localhost:3000 com seu navegador para interagir com a aplicação.
O servidor backend deve ser iniciado antes para que você possa interagir com sucesso com a aplicação.
