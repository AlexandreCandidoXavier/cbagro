# Apresentação no XXIII Congresso Brasileiro de Agrometeorologia (CBAGRO/2025)


Para rodar o *Netebook* da apresentação 
("apresentacao_cbagro.ipynb") no seu computador, 
terá:

  * instalar o programa [GIT](https://git-scm.com/downloads);
  * Depois de instalado o GIT, copiar este repositório para o 
seu computador. No *prompt* do terminal do Git (*Git CMD*), 
vá para pasta onde será copiado o repositório e execute:

```
git clone https://github.com/AlexandreCandidoXavier/cbagro.git`
```

  * instalar um ambiente Python, sugiro utilizar o distribudor
[Anaconda miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main)
  * No *Anaconda Prompt* vá para a pasta onde você 
baixou o repositório:
  * Crie o ambiente *cbagro*

```
conda create --name cbagro
```
  * ative o ambiente:
```
conda activate cbagro
```
  * Instale o "pip"
```
conda install pip
```
  * instale as bibliotecas necessárias
```
pip install -r requirements.txt
```
  * abra o *Jupyter-Lab*
```
jupyter lab
```
  * No *Jupyter-Lab* abra o notebook
"apresentacao_cbagro.ipynb" 

Para quem tem familiaridade com sistema Ubuntu, 
no terminal do sistema operacional vá para o diretório do 
repositório onde foi criado e aplique os comandos no terminal:

```
$ python -m venv cbagro
$ source cbagro/bin/activate
$ pip install -r requirements.txt
$ jupyter lab
```

Ainda será necessário criar uma pasta com os arquivos da base 
BR-DWGD (para baixar, [aqui](https://ufesbr-my.sharepoint.com/:f:/g/personal/alexandre_xavier_ufes_br/Esmad63PHqBNoICoqO3XErQBWj9WrMv4X1ny0_ltgUKkdA?e=BiKiRd) ou [aqui](https://drive.google.com/drive/folders/11-qnvwojirAtaQxSE03N0_SUrbcsz44N)):

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


