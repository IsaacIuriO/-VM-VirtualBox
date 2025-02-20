# Ambiente Virtual Educacional

## Introdução ✓
Este projeto tem como objetivo criar um ambiente virtual para fins educacionais, que possibilite a execução de softwares como MySQL, Node.js e Python. A atividade integra conceitos de Sistemas Operacionais, Redes de Computadores, Levantamento de Requisitos e Lógica de Programação. Nele, você pesquisará componentes para a montagem de um computador com custo máximo de R$5.000,00, e será configurado uma máquina virtual e instalado uma distribuição Linux gratuita, escolhida com base na compatibilidade e facilidade de uso.

## Levantamento de Requisitos ✓

- Requisitos Funcionais: O computador construído comporta facilmente os softwares (MySQL, Node.js e Python) requisitados para o uso educacional (banco de dados, desenvolvimento web e programação). Além de ser estável para o desenvolvimento e testes.

- Requisitos Não-Funcionais: O computador físico está dentro do limite de R$5.000,00 proposto, com o financeiro usado eficientemente, além de comportar e rodar as tarefas requisitadas.

### Requisitos para o Computador Físico ✓
- ~Processador (*CPU*)~ ✓
- ~Memória RAM~ ✓
- ~Armazenamento~ ✓
- ~Placa-mãe~ ✓
- ~Fonte de Alimentação~ ✓
- ~Teclado~ 
- ~Mouse~ 
- ~Monitor~ ✓
- ~Outros (placa de vídeo, cooler do processador)~ ✓
- **Orçamento Máximo:** ~R$ 5.000,00~ ✓

## Orçamento ✓

**Geral**: [PC Completo](https://meupc.net/build/bb3rq9)

- **Processador**: [AMD Ryzen 5 4500 3.6 GHz 6-Core](https://meupc.net/link/Kabum/Fs6rE3)

- **Memória RAM**: [Kingston Fury Beast (Preto) 16 GB (2x8GB)](https://meupc.net/peca/64gcGS/memoria-kingston-fury-beast-kf432c16bbk216)

- **Armazenamento**: [Kingston SSD A400 480 GB 2.5"](https://meupc.net/peca/kwi558/ssd-kingston-a400-a400480gb)

- **Placa-mãe**: [Asus TUF Gaming A520M-Plus Micro ATX AM4](https://meupc.net/peca/UMx2r9/placa-mae-asus-tuf-gaming-a520m-plus)

- **Fonte**: [Gamemax 600W 600 W Certificado 80+ White  ATX12V](https://meupc.net/peca/cU63BA/fonte-gamemax-600w)

- **Teclado**: [Redragon Kumara](https://meupc.net/peca/AB2fS8/teclado-redragon-kumara-k552)

- **Mouse**: [Redragon Cobra Chroma M711 Com fio](https://meupc.net/peca/jwq68q/mouse-redragon-cobra-chroma-m711)

- **Monitor**: [Monitor  AOC 24G2E1 23.8″ 1920 x 1080 100 Hz](https://meupc.net/peca/Ho28is/monitor-aoc-24g2e1)

- **Outros**:

  - **Placa de vídeo**: [MSI GeForce GTX 1650 4 GB VENTUS XS](https://meupc.net/peca/bxq9r8/placa-video-msi-geforce-gtx-1650-geforcegtx16504gb)

  - **Gabinete**: [Rise Mode Galaxy Glass M Mini (Preto) MicroATX Mini Tower](https://meupc.net/peca/baF42G/gabinete-rise-mode-galaxy-glass-m-mini-rmgaggmnfb)

  - **Cooler do Processador**: [Rise Mode Gamer G800 Hidráulico](https://meupc.net/peca/PX3X42/cooler-processador-rise-mode-gamer-g800)

  - **Mousepad**: [Havit HV-MP830](https://meupc.net/peca/qWqF98/mousepad-havit-hv-mp830-hvmp830)


Total no cartão: **R$4.873,55**

Total no boleto **R$4.249,62**

## Escolha do Sistema Operacional ✓

### Ubuntu
Utilizaremos o sistema operacional Linux, com sua distribuição alternativa Ubuntu devido a suas qualidades. Este sistema operacional fornece uma comunidade muito acolhedora, que possui fóruns e tutoriais para soluções de problemas, permitindo que o uso educacional seja mais efetivo para o desenvolvimento das habilidades dos alunos.

![UBUNTU](https://s2.glbimg.com/AnXNMtY3VON9i-ZO89UgGFg1X2g=/288x0/s.glbimg.com/jo/g1/f/original/2016/07/18/ubuntulogo.png)


## Máquina Virtual (VM Virtual Box)

### Requisitos para a Máquina Virtual
- **Processador (CPU):** ???
- **Memória RAM:** É necessário ter 4GB RAM no mínimo para o programa não ficar lento.
- **Armazenamento:** 10 GB de HD
- **Rede:** Configuração via NAT para acesso à internet, pois iremos necessitar que outro dispositivo se conecte à rede e sem necessidade de configurar a internet.

### Pré-requisitos

- **Imagem ISO do Linux:** Faça o download da imagem ISO do Ubuntu em [Ubuntu Download](https://ubuntu.com/download).

### Passo a Passo

#### 1. Instalação do VirtualBox
- **VirtualBox:** Baixe e instale a versão mais recente do [https://www.virtualbox.org/wiki/Download_Old_Builds_5_1)

Instruções para instalação do VirtualBox:

1° Clique neste link: [VirtualBox](https://www.virtualbox.org/wiki/Download_Old_Builds_5_1). E instale a versão mais recente do VirtualBox VM.

2° Pressione o botão de download para iniciar a instalação, como mostrado na imagem:

![image](https://github.com/user-attachments/assets/d0b31223-249d-4403-b933-864f7c9f23d2)

3° Pressione o botão de aceitar os termos e baixe o arquivo no seu computador, como mostrado na imagem:

![image](https://github.com/user-attachments/assets/7a5ebf67-3f78-4657-9294-6909651156bc)

4° Abra o arquivo baixado para instalar o VirtualBox:

![image](https://github.com/user-attachments/assets/e8461b24-736b-4c33-86f4-10cb24be7a0e)

#### 2. Instalando o Ubuntu

- Após isso, devemos instalar o Ubuntu, para realizar essa tarefa, é preciso entrar no site do sistema operacional e baixar a versão mais recente [Ubuntu Download](https://ubuntu.com/download):

![image](https://github.com/user-attachments/assets/c581e2e1-4dac-46b4-b66b-8d7226a8211a)

#### 3. Criação da Máquina Virtual

1° Selecione a opção “Novo” em seu VirtualBox:

![image](https://github.com/user-attachments/assets/cd380b3a-7189-4e5e-b0a9-5735ee8bdcb4)

2° Nomeie o seu espaço virtual e selecione o arquivo baixado do Ubuntu na opção “Imagem ISO”:

![image](https://github.com/user-attachments/assets/41912042-0d12-48f8-9913-29bc6449044e)

![image](https://github.com/user-attachments/assets/3ba2857a-7996-4b4c-ae11-c6957debd76f)

3° Defina a Memória Base com 4000 MB e 4 Processadores:

![image](https://github.com/user-attachments/assets/24bf743b-1f82-4d56-9cc2-b3ec62a14ada)

4° Crie um novo Disco Rigído Virtual com o tamanho baixo de 25 GB:

![image](https://github.com/user-attachments/assets/0d8d8f29-ae41-4d98-add8-8ec0e4de9dd9)

5° Com o sumário a mostra, analise se suas especificações foram atendidas e selecione a opção “Finalizar”:

![image](https://github.com/user-attachments/assets/a873ba6f-16fb-4d25-b8f8-9fc61629911f)

6° Inicie seu espaço virtual pressionando o botão “Iniciar”:

![image](https://github.com/user-attachments/assets/165f3aed-ef16-46b5-b06e-0f16a4522a82)

7° Quando iniciado, essa aba aparecerá, utilize as setas para se locomover, selecione pressione a tecla “Enter” para continuar:

![image](https://github.com/user-attachments/assets/6e81dafe-8c87-480d-9704-268bb0bb7304)

8° Personalize seu sistema operacional...

![image](https://github.com/user-attachments/assets/a5f23262-fa24-4957-aca6-59f8351c6929)

Pronto! Seu sistema operacional está configurado para uso!

#### 4. Configuração de Rede

O modo que escolhemos, entre NAT e Bridge, foi o NAT, pois não necessita configurar a rede para utilizá-lo.

1° Feche o Computador Virtual e abra o VirtualBox novamente:

![image](https://github.com/user-attachments/assets/b4f98ed2-faad-4d3a-81e7-f7cdab625626)

2° Selecione o Computador Virtual:

![image](https://github.com/user-attachments/assets/5c043f31-f903-4e59-9f3f-ef27ef6dc307)

3° Clique duas vezes em "Configurações":

![image](https://github.com/user-attachments/assets/0eb71a40-4309-40cd-a904-a35bf6d4b7f5)

4° Selecione "Rede":

![image](https://github.com/user-attachments/assets/ea0df2dc-30cb-460c-851b-881a6a0102dc)

5° Em "Adaptor 1", habilite a placa de rede, e das opções em "Conectado a:", selecione "NAT":

![image](https://github.com/user-attachments/assets/65b2edca-c990-4043-813f-982d7d427164)

Pronto! Sua Rede está configurada!

#### 5. Comandos básicos no Terminal

- Abra o terminal a partir da combinação: "Ctrl+Alt+T":

![image](https://github.com/user-attachments/assets/82075217-1d21-438f-bad1-2243ed148928)

- Com isso, utilize códigos como esses:

  - `mysql --version`
    ![image](https://github.com/user-attachments/assets/aebcab2e-dc45-4d2d-90f8-e5385004f73f)
    
  - `node -v`
    ![image](https://github.com/user-attachments/assets/a6af6f74-ba79-4d28-8db8-dfeec75183c2)
    
  - `python3 --version`
    ![image](https://github.com/user-attachments/assets/85655209-684e-4120-9526-a3c2d2e0f1da)

##Considerações Finais
