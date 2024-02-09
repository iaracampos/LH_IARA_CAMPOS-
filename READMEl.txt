Guia de Configuração e Execução do Projeto

Este guia fornecerá instruções passo a passo para configurar e executar o projeto.

Pré-requisitos

Antes de iniciar, certifique-se de ter as seguintes ferramentas instaladas em seu ambiente:

    Visual Studio Code (VSCode)
    Python 3

Configuração do Ambiente Virtual

    Abra um terminal no diretório do seu projeto.

    Execute o seguinte comando para criar um ambiente virtual:

    bash

python -m venv nome_da_venv

Ative o ambiente virtual. No Windows, use o seguinte comando:

bash

nome_do_ambiente\Scripts\activate

No Linux ou macOS, use:

bash

    source nome_do_ambiente/bin/activate

Instalação de Dependências

    Com o ambiente virtual ativado, instale as dependências usando o seguinte comando:

    bash

    pip install numpy pandas seaborn matplotlib scikit-learn

    Este comando instalará as bibliotecas necessárias para análise de dados, visualização e aprendizado de máquina.

Execução do Projeto

    Abra o Visual Studio Code no diretório em que você salvou o projeto. 

Execute o script Python usando o seguinte comando no terminal do VSCode:

bash

python main.py