# Reconhecimento de máscara em vídeos
## Reconhecimento facial em vídeos utilizando Python em um ambiente Anaconda

##### OBS: Esse passo a passo considera que a instalação do Anaconda Navigator já tenha sido realizada com antecedência.

### **1° Passo - preparando o ambiente**

#### Entre na seção de ambientes a partir da aba esquerda do Anaconda Navigator;
#### Crie um novo ambiente com python 3.6 ou 3.7 (qualquer outra versão irá falhar o projeto e ele terá de ser reiniciado);
#### No menu direito, onde se encontram os packages, selecione na aba de visualização os "não instalados" e pesquise pelas bibliotecas "tensorflow" e "mtcnn" e as instale.
##### OBS: Caso não encontre a biblioteca mtcnn, abra o anaconda prompt e digite os seguintes comandos:
```
$ conda activate (nome do ambiente que você criou)
$ pip install mtcnn
```
### **2° Passo - organizando os códigos e arquivos**

#### Instale os códigos deste diretório em uma pasta específica, de preferência com o mesmo nome do ambeinte que criou no Anaconda;
#### Voltando para a seção "Home" do Anaconda, selecione um aplicativo para utilizar no ambiente (recomendo o Visual Studio Code, que é no qual me baseio nos passos a seguir);
#### Dentro do aplicativo, abra a pasta com os arquivos baixados 
