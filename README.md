# ML_Environment
Autor: Gianni S. S. Liveraro

Data: 22-10-2023

Descrição: Scripts básicos para criar ambientes (conda) para uso de Machine Learning


# Instruções
- Clone este repositório
  
- Instale a versão mais recente do miniconda com os seguintes comandos:
                        
                        mkdir -p ~/miniconda3
                        wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
                        bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
                        rm -rf ~/miniconda3/miniconda.sh
                        ~/miniconda3/bin/conda init bash
                        ~/miniconda3/bin/conda init zsh
                        source ~/miniconda3/etc/profile.d/conda.sh

- Crie um ambiente e o acesse via:
  
                        conda create --name ENV_NAME
                        conda activate MLEnv

- Instale as dependências básicas:
  
                        pip install -r requirements.txt

- Caso o pip não esteja instalado no ambiente:
  
                        conda install pip

- Feito!
