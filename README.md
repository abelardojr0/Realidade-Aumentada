# Realidade-Aumentada

Acesse: https://developer.vuforia.com/home

Crie sua Conta

Faça seu Login 

Navegue até Downloads: https://developer.vuforia.com/downloads/sdk

Faça o download do SDK para Unity

Volte para sua conta: https://developer.vuforia.com/develop/dashboard

Naguegue até Planos e Lincensas:  https://developer.vuforia.com/develop/licenses

Crie uma licensa básica, clicando em "Gerar licensa básica", coloque o nome da sua licensa e confirme.

Clique na sua licensa e copie a Chave da Licensa.

Depois navegue até Gerenciador de Alvos: https://developer.vuforia.com/develop/databases

Gere um database clicando no botão, coloque o nome e deixe selecionado Device.

Clique no database criado, clique em Adicionar Alvo.

Selecione a opção Image, clique em escolher arquivo, navegue no seu computador e encontre a imagem correspondente.

Mude o Width para 1 (proporção) e coloque um nome na sua imagem, repita esse procedimento para todos os seus alvos.

Baixe o banco de dados, escolhe Unity Editor.

Agora seu vuforia está configurado.









Vamos baixar e instalar o Unity Hub

Navegue até o site de download da unity: https://unity.com/pt/download

Clique no botão de baixar e aguarde o download do executável.

Siga o passo a passo da instalação.

Abra seu Unity Hub

Clique em Installs, clique em Install Editor

Baixe a versão 2021.3.45f1 LTS

Ela será necessária para a integração com o Vuforia

Aproveita na instalação e já baixe também os pacotes android.

Após instalação concluída, navegue até Projects

Clique em New Project

Mude a versão para a 2021.3.45f1 LTS

Coloque o nome no seu projeto.

Selecione a opção: 3D (Build-In Render Pipeline)

Selecione ou não o local de instalação e clique em Create Project.

Aguarde a criação do seu ambiente 3D da Unity.

Clique em Assets > Import Package

E procure pelo SDK do vuforia que você baixou, selecione e quando abrir clique em Import.

Ele vai pedir para atualizar, clique em Update e aguarde.

Repita o mesmo procedimento para importar o seu banco de dados criado no vuforia

E novamente para importar o package disponibilizado de modelos 3D.

Vá em Game Object > Vuforia Engine > AR Camera

Apague sua Main Camera

Clique na AR Camera e no menu lateral (Inspetor) clique em: Open Vuforia Engine configuration

E no campo App License Key, cole sua chave gerada no site da Vuforia

Clica fora para fechar.

Vá em GameObject > Vuforia Engine > Image target

Em Image Target Behaviour (Script), em Type Selecione From Database

Em Database selecione seu banco de dados baixado da Vuforia

Em Image Target selecione qual seu alvo.

Navegue até a pasta Course_Library > Animals > Dogs 

Selecione o cachorro alvo que você escolheu, clique e arraste para dentro do ImageTarget que foi criado.

Opcionalmente renomei o ImageTarget.

Ajuste a proporção da imagem 3D.

Salve seu projeto (Crtl + S)

Se você estiver usando notebook pode clicar no botão de Play que fica centralizado no programa e testar.

Caso queira exportar para Android exige uma configuração:

Clique em File > Build Settings > Android > Switch Plataform

Clique em Player Settings > Other Settings

Mude: Minimum API Level para Android 8.0 'Oreo' (API Level 26)

Scripting BackEnd para: IL2CPP

Target Architectures para: ARM64 e desmarque o ARMv7

Feche o Player Settings e agora você tem duas opções:

Build, caso você queira baixar o arquivo APK para usar depois, ou transferir para um drive ou algo do tipo.

Build and Run essa opção só é possível se você estiver com seu dispositivo conectado a máquina e selecionado no campo Run Device

Para permitir a conexão do dispositivo você tem que ir nas configurações do seu celular, ativar o modo Desenvolvedor e ativar o Depurador USB.






