# monkey-stocks

Backtesting de uma estratégia de seleção aleatória de portfolio baseada em [monkey stocks](https://www.instagram.com/monkeystocks/?hl=pt-br).

## Instalação

Crie um ambiente virtual
```
$ virtualenv .venv
```

Ative o ambiente virtual

```
$ source .venv/bin/activate
```

Instale os requirements (bibliotecas python para execução dos códigos)

```
$ pip install -r requirements.txt
```

Adicione o ambiente virtual a sua base de kernels do jupyter notebook

```
$ python -m ipykernel install --user --name=.venv
```

**Obs:** É possível remover o ambiente virtual de sua lista de kernels executando o comando

```
$ jupyter kernelspec uninstall .venv
```

Após executar esse comando espera-se um resultado como o seguinte

```
Installed kernelspec .quantenv in /home/user/.local/share/jupyter/kernels/.venv
```

Inicie o Jupyter Notebook

```
$ jupyter notebook
```

E por fim, na barra de navegação clique em **kernel/change kernel** e altere o kernel para .venv


