# Consumo de APIs com Python e Padrão de Projeto Strategy

Este repositório contém a implementação de um desafio técnico da aula de Desenvolvimento Web 3, utilizando Python e o padrão de projeto Strategy para consumo de APIs.

## Introdução

Este projeto demonstra como utilizar o padrão de projeto Strategy para consumir diferentes APIs de maneira eficiente. As APIs utilizadas incluem Pokémon, Rick and Morty, Star Wars e A Song of Ice and Fire.

## Requisitos

- **Python**: Versão 3.12.2

Para instruções sobre a instalaçao do Python, consulte [este link](https://python.org.br/instalacao-windows/) (Windows) ou [este](https://python.org.br/instalacao-linux/) (Linux).

## Instalação e Execução

Para executar o projeto, siga os passos abaixo:

### Clonagem e Configuração do Projeto

1. **Clonar o repositório**:
   ```bash
   git clone https://github.com/bruno-santos382/consumo_API_2025.git
   ```

2. **Acessar a pasta do projeto**:
   ```bash
   cd consumo_API_2025
   ```

### Configuração do Ambiente Virtual

#### No Windows:

1. **Criar um ambiente virtual**:
   ```bash
   python -m venv ambiente
   ```

2. **Iniciar o ambiente**:
   ```bash
   .\ambiente\Scripts\activate.bat
   ```

3. **Instalar dependências**:
   ```bash
   pip install -r requirements.txt
   ```

#### No Linux:

1. **Criar um ambiente virtual**:
   ```bash
   python3 -m venv ambiente
   ```

2. **Iniciar o ambiente**:
   ```bash
   source ambiente/bin/activate
   ```

3. **Instalar dependências**:
   ```bash
   pip install -r requirements.txt
   ```

### Execução do Projeto

Após configurar o ambiente, execute o programa com o seguinte comando:
```bash
python main.py
```

## Saída Esperada

A saída do programa deve ser semelhante à seguinte:

```console
Consumo da API Pokémon
****************************************
(1, 'bulbasaur')
(2, 'ivysaur')

Consumo da API Rick and Morty
****************************************
(1, 'Rick Sanchez', 'Human')
(2, 'Morty Smith', 'Human')

Consumo da API Star Wars
****************************************
('Luke Skywalker', ['https://swapi.dev/api/films/1/', 'https://swapi.dev/api/films/2/', 'https://swapi.dev/api/films/3/', 'https://swapi.dev/api/films/6/'])
('C-3PO', ['https://swapi.dev/api/films/1/', 'https://swapi.dev/api/films/2/', 'https://swapi.dev/api/films/3/', 'https://swapi.dev/api/films/4/', 'https://swapi.dev/api/films/5/', 'https://swapi.dev/api/films/6/'])

Consumo da API Crônicas do Gelo e do Fogo
****************************************
('Jon Snow', ['Season 1', 'Season 2', 'Season 3', 'Season 4', 'Season 5', 'Season 6'])
('Walder', ['Season 1', 'Season 2', 'Season 3', 'Season 4', 'Season 6'])
```
