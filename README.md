# Projeto Final: State Of Data Brazil


Este repositório é destinado ao Projeto Final do curso do EBA

## INSTRUÇÕES PARA REALIZAÇÃO DO PROJETO FINAL:

**Proposta geral:** "Quais são os fatores associados aos salários na área de dados no Brasil?"



**Etapa 1 - Análise descritiva**

- Entender as características gerais dos dados e observando de forma descritiva o que pode estar relacionado com o salário.


**Etapa 2 - Testes de hipóteses paramétricos e intervalo de confiança**

- Existe alguma variável que esteja relacionada com os salários? É possível comprovar isso com testes de hipótese? 

**Etapa 3 - Regressão logística**

Ajustar uma regressão logística para variável resposta salário acima/abaixo de x. 


Caso você queira, faça o desafio sozinho antes de ver as aulas! Use as aulas apenas para complementar seu conhecimento e ver outras abordagens!


## INSTRUÇÕES PARA O USO DESTE REPOSITÓRIO:

### **Como utilizar este repositório?**

Este repositório contém os arquivos e códigos necessários para a aula de Estatística Descritiva. Abaixo estão as instruções simplificadas para configurar o ambiente com Pyenv e Poetry.

- **Passo a Passo para Configuração do Ambiente:**

1. **Clonar o Repositório:**

No terminal, clone este repositório:

```bash
git clone https://github.com/EbaPed/Projeto-Final-StateOfDataBrazil.git
cd Projeto-Final-StateOfDataBrazil
```

2. **Configurar a versão do Python com Pyenv**

Defina a versão do Python para o projeto. Para esta aula, vamos usar o Python 3.10.11 (ou outra versão compatível):

```bash
pyenv local 3.10.11
```

3. **Ativar o Ambiente Virtual Poetry**

Agora, ative o ambiente virtual:

```bash
poetry shell
```

4. **Instale as dependências do projeto usando Poetry:**

```bash
poetry install
```

Isso criará automaticamente um ambiente virtual isolado.


5. **Configurar o Kernel do Jupyter Notebook**

Se você for usar Jupyter Notebook, instale o ipykernel:

```bash
poetry add ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)
```

No Jupyter Notebook, escolha o kernel "Python (venv)" ao iniciar ou criar um novo notebook.


6. **Desativar o Ambiente Virtual**

Para sair do ambiente virtual, basta usar:

```bash
exit
```

7. **Executar o Código**

Agora que o ambiente está configurado, você pode executar os códigos Python fornecidos no repositório.

### **Comandos úteis**

- Ativar o ambiente virtual Poetry:

```bash
poetry shell
```

- Rodar um script com Poetry:

```bash
poetry run python script.py
```

- Adicionar bibliotecas:

 ```bash
poetry add nome_da_biblioteca
```

- Remover Bibliotecas:

 ```bash
poetry remove nome_da_biblioteca
```
