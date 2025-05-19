RASTREAMENTO DE OBJETOS

DESCRIÇÃO DO PROJETO
Este projeto permite rastrear objetos e identificá-los com base em suas formas, usando técnicas de visão computacional e aprendizado de máquina.

ISTALAÇÃO:
1. Instale o Visual Studio Code (VS Code).
2. Instale o Anaconda Navigator.
3. (Opcional) Instale o Iriun Webcam no computador e celular, se não tiver webcam no PC.
4. Crie o modelo de reconhecimento no Teachable Machine:
5. Treine com os objetos desejados.
6. Exporte o modelo no formato Keras (.h5).
7. Baixe o arquivo classificacao_5_objetos-v4.py.
8. Baixe o arquivo env_teste_PI_2024.yml com o ambiente virtual já configurado.

COMO USAR:
1. Crie uma pasta para o projeto.
2. Coloque o modelo .h5 e o arquivo classificacao_5_objetos-v4.py nessa pasta.
3. Abra o Anaconda Navigator.
4. Vá em Environments e importe o ambiente com o arquivo env_teste_PI_2024.yml.
5. Com o ambiente ativado, abra o VS Code pelo Anaconda.
6. No VS Code, abra a pasta do projeto e o arquivo classificacao_5_objetos-v4.py.
7. Verifique se o ambiente env_teste_PI_2024 está selecionado.
8. Execute o projeto.

ATENÇÃO:
Se aparecer erro ao carregar o modelo, veja se o nome do arquivo está como keras_model.h5 (com underline). Se estiver com ponto, renomeie o arquivo, não altere o código.

CRÉDITOS:
Este projeto foi desenvolvido como parte das atividades do Laboratório de Sistemas de Informação da Universidade Federal do Oeste do Pará (UFOPA).
