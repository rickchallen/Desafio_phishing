# Desafio_phishing
Desafio de Phishing do Bootcamp de Cibersecurity Santander Com A DIO

- Acesso root no Terminal: sudo su
- Iniciando o setoolkit: setoolkit
- Tipo de ataque: Social-Engineering Attacks
    -  ![Descrição da imagem](https://github.com/rickchallen/Desafio_phishing/blob/main/Passo_2_kali_2024-12-15_09-10-33.png)

- Vetor de ataque: Web Site Attack Vectors
    -  ![Passo 3](https://github.com/rickchallen/Desafio_phishing/blob/main/web_sites_attacks_vectors_passo3_2024-12-15_09-13-44.png)


- Método de ataque: Credential Harvester Attack Method
   -  ![Descrição da imagem](https://github.com/rickchallen/Desafio_phishing/blob/main/credencials.png)
- Método de ataque: Custom Import Vamos Utilizar esse metodo por que o Facebook Adotou um mecanismo de defesa que impede a clonagem direta através da opção  Site cloner
   -  ![Descrição da imagem](https://github.com/rickchallen/Desafio_phishing/blob/main/custom_import_passo5_2024-12-15_09-17-02.png)
- Salve a página do facebook e também inspecione o botão login e anote seu id.
   -   ![Descrição da imagem](https://github.com/rickchallen/Desafio_phishing/blob/main/Capturar.jpg)
   -   Renomear a página salva para index.html, pois o setookit usa esse nome por padrão.
   -   ![Descrição da imagem](https://github.com/rickchallen/Desafio_phishing/blob/main/Capturar17.jpg)
- Salvar no index.html o codigo Fonte Online do facebook
   - ![Descrição da imagem](https://github.com/rickchallen/Desafio_phishing/blob/main/codigofonte_online.jpg)
- Ao procurarmos id do botão veremos onde ele está sendo manipulado no código fonte. Isso deu uma dica rápida de qual chamada de script deveria ser deletada.
   -   ![Descrição da imagem](https://github.com/rickchallen/Desafio_phishing/blob/main/Capturar24.jpg)
- Agora Vamos remover o Script
   - ![Descrição da imagem](https://github.com/rickchallen/Desafio_phishing/blob/main/removendo_script.jpg)
- Agora vamos continuar  no settoolkit com a opção custom import
   - ![Descrição da imagem](https://github.com/rickchallen/Desafio_phishing/blob/main/custom_import_passo5_2024-12-15_09-17-02.png) 
- Obtendo o endereço da máquina: ifconfig
- URL para clone: http://www.facebook.com
