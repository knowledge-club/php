# Como instalar o PHP

- [Ubuntu](#ubuntu)
- [Windows](#windows)

O processo de instalação do xampp é bem parecido nos principais sistemas operacionais

## Como Instalar o PHP no Ubuntu <a name="ubuntu"></a>

1. Vá para [XamppInstaller](https://www.apachefriends.org/pt_br/download.html)
2. Clique em download na versão 7.x
3. Abra o seu terminal ctrl + alt + t.
4. Digite o seguinte comando ```cd Downloads.```
5. Altere a permissão de seu instalador ```chmod 755 xampp-linux-xxx-installer.run```
6. Em seguida digite ```./xampp-linux-xxx-installer.run``` Onde xxx é a versão que você escolheu
7. [Instalando o Xampp](#instalando_xampp)

### Abrindo o xampp panel
1. Para abrir o xampp panel abra o terminal ctrl + alt + t  Digite: ```cd /opt/lampp```
2. Em Seguida ```sudo chmod 777 manager-linux-xxx.run ```
3. e ```sudo ./manager-linux-x64.run```
4. Pronto o seu xampp panel já está sendo executado.

## Como Instalar o PHP no Windows<a name="windows"></a>

1. Vá para [XamppInstaller](https://www.apachefriends.org/pt_br/download.html)
2. Clique em download na versão 7.x
3. Quando for solicitado o download, clique em "Salvar" e aguarde o download terminar.
4. Assim que terminar o download, Abra o instalador
5. [Instalando o Xampp](#instalando_xampp)
6. Na área de trabalho clique no ícone do xampp.
8. Você também poderá iniciar os outros componentes, caso pretenda usá-los.

Pronto seu xampp já está instalado!

## Instalando o Xampp<a name="instalando_xampp">

- [O que é Xampp?](#xampp)

1. Ao executar o instalador aparecerá a janela de instalação do xampp
![Instalando o xampp](../../images/xampp1.png)

2. Clique em "Next" irá aparecer a seguinte janela
![Instalando o xampp](../../images/xampp2.png)

3. Clique em "Next"
![Instalando o xampp](../../images/xampp3.png)

4. Clique mais uma vez em "Next"
![Instalando o xampp](../../images/xampp4.png)

5. "Next", mais uma vez. Aguarde a instalação:
![Instalando o xampp](../../images/xampp5.png)

6. Quando terminar, esta será a última janela:
![Instalando o xampp](../../images/xampp6.png)

7. Clique em "Finish" e abrirá a seguinte janela:
![Instalando o xampp](../../images/xampp7.png)

8. Selecione o seu Apache Web Server e clique em "Start"
9. Abra seu navegador e digite localhost e o seu apache server já está pronto.


## O que é Xampp<a name="xampp">
XAMPP é um servidor independente de plataforma, software livre, que consiste principalmente na base de dados MySQL, o qual foi substituído pelo MariaDB, o servidor web Apache e os interpretadores para linguagens de script: PHP e Perl. O nome provem da abreviação de X (para qualquer dos diferentes sistemas operativos), Apache, MariaDB, PHP, Perl. É um método que torna extremamente fácil para os desenvolvedores a criar um servidor web local para fins de teste.
