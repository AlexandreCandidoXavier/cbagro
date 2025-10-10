# Apresentação no XXIII Congresso Brasileiro de Agrometeorologia (CBAGRO/2025)


Para rodar o *Netebook* da apresentação 
("apresentacao_cbagro.ipynb") no seu computador, 
terá:

## Copiar repositório
  * Instalar o programa [GIT](https://git-scm.com/downloads). Para copiar este repositório no 
seu computador, no *prompt* do terminal do Git (*Git CMD*), 
vá para pasta onde deseja copiar o repositório e execute:

```
git clone https://github.com/AlexandreCandidoXavier/cbagro.git
```

## Rodando com o *Anaconda miniconda*
  * Instalar o distribuidor [Anaconda miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main)
  * No *Anaconda Prompt* vá para a pasta onde você 
baixou o repositório.
  * Crie o ambiente que vamos nomina-lo de *cbagro* com o comando:

```
conda create --name cbagro
```
  * Ative o ambiente *cbagro*:
```
conda activate cbagro
```
  * Instale o "pip":
```
conda install pip
```
  * Instale as bibliotecas necessárias:
```
pip install -r requirements.txt
```
  * Abra o *Jupyter-Lab*
```
jupyter lab
```
  * No *Jupyter-Lab* abra o notebook "apresentacao_cbagro.ipynb".

Uma vez que você criou o ambiente *cbagro*,
não haverá mais a necessidade de criar um novo ambiente para uma
segunda vez de uso do *Notebook*, apenas: no
*Anaconda Prompt*, na pasta do repositório, ativar o 
ambiente *cbagro* (`conda activate cbagro`) e abrir o *Jupyter-Lab*
(`jupyter lab`).

## Rodando no *Linux*

Para quem tem familiaridade com sistema Linux, depois de ter feito
uma cópia do repositório (`git clone https://github.com/AlexandreCandidoXavier/cbagro.git`), 
no *terminal* e estando no diretório do 
repositório *cbagro*:

```
$ python -m venv cbagro
$ source cbagro/bin/activate
$ pip install -r requirements.txt
$ jupyter lab
```

## Outros arquivos necessários

Ainda será necessário criar uma pasta com 
arquivos da base BR-DWGD apresentados
abaixo,  (para baixar, [aqui](https://ufesbr-my.sharepoint.com/:f:/g/personal/alexandre_xavier_ufes_br/Esmad63PHqBNoICoqO3XErQBWj9WrMv4X1ny0_ltgUKkdA?e=BiKiRd) ou [aqui](https://drive.google.com/drive/folders/11-qnvwojirAtaQxSE03N0_SUrbcsz44N)). 

No *Jupyter lab*, no notebook "apresentacao_cbagro.ipynb", na
célula de importação das bibliotecas, 
atribuir à variável `path` o caminho correto da pasta
onde você fez o "download" dos arquivos, por exemplo no Windows:

```path = 'C:\\Users\\Acer\\Desktop\\dados_BR-DWGD\\```.

No caminho tem que ter "\\" dupla e não esqueça de 
colocar "\\\\" no final!


Arquivos necessários:

```
pr.npz
Tmax.npz
ETo_19610101_19801231_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
ETo_19810101_20001231_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
ETo_20010101_20240320_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
pr_19610101_19801231_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
pr_19810101_20001231_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
pr_20010101_20240320_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
Tmax_19610101_19801231_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
Tmax_19810101_20001231_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
Tmax_20010101_20240320_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
Tmin_19610101_19801231_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
Tmin_19810101_20001231_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
Tmin_20010101_20240320_BR-DWGD_UFES_UTEXAS_v_3.2.3.nc
```


