# Integração de ROS com a IDE Visual Studio Code
Configuração automática do ambiente ROS
Permite iniciar, parar e ver status do ROS Master
Syntax highlighting dos arquivos .msg, .urdf, .srv e outros


## Instalar VSCode
https://code.visualstudio.com/


## Instalar Extensão para ROS

Abra VScode
dê Ctrl+P e cole o comando "ext install ajshort.ros"


## Utilização
Assumindo que seus diretórios esteja na forma ~/WORKSPACE_PATH/src/..., 
Vá para a raiz da sua workspace: cd ~/WORKSPACE_PATH
nesse momento a extensão já irá reconhecê-la.
Se necessário, executar no terminal catkin_make

Como VSCode cria arquivos de configuração na sua workspace, é sempre recomendado
enquanto utilizar ela, deixar o VSCode aberto no diretório raiz da sua workspace.

## Opcional
Usar alguma extensão para C/C++, recomendo **vscode-cpptools**

### Mais informações em:
http://wiki.ros.org/IDEs#Visual_Studio_Code_.28VSCode.29
