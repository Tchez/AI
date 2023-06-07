# Projeto Actor-Critic
Este é um projeto que utiliza uma rede de ator-crítico, que é um tipo de algoritmo de aprendizado por reforço, onde o agente aprende a realizar ações que maximizam algum valor de recompensa. A rede de ator-crítico consiste em duas partes: o "ator", que escolhe ações, e o "crítico", que avalia as ações escolhidas pelo ator.

<br/>

## Como rodar a aplicação

<br/>

Crie e habilite um ambiente virtual

```console
  python -m venv venv
```

```console
  venv\Scripts\activate | windows
  .venv/bin/activate | linux e macOs
```

Instale as dependências do projeto

```console
  pip install -r requirements.txt
```

<br/>

## Uso

Inicialize o processo de treinamento rodando o arquivo main.py:

```console
  python main.py    
```