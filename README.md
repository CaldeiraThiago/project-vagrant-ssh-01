## Repositório de estudos do Vagrant

🔭 Atualmente estou estudando IaC (Infraestrutura como código). E este repsoitório contém os estudos relativos a ferramenta Vagrant.

Foi criado um máquina virtual pelo Vagrant através de linha de código. Essa virtual machine contém:

- A imagem da hashicorp/bionic64 que é a imagem oficial da desenvolvedora do Vagrant;
- Um servidor web nginx que opera na pora 8080;
- Um IP público fixado em modo bridge, que utiliza a saída da placa de rede wi-fi;
- Um script provisionado em shell, que tem como objetivo criar a máquina virtual com o servidor Nginx instalado e operando;
- Sincronismo de um página html de uma API dos correios que está salva no host, e se conecta no servidor web da máquina virtual;
