![image](https://github.com/Lafossato/Fedora-Linux/assets/92603640/50885d0f-39eb-4d76-a011-b3d6eacc11b1)

# Fedora-Linux

**Criar um container com o Debian que seja interaivo e dentro dele esteja o neofetch**
  - Ir ao comando(cmd);
 O Comando é a onde poderá colocar os código.
  - Instal o Debian(podman);
 sudo dnf install -y podman
  - Irá direcionar dentro do Debian;
 sudo podman run -it debian bash
  - Vai atualizar o Debian;
 apt-get uptade
  - Install o neofetch;
 apt-get install -y neofetch
  -Escrever: neofetch
