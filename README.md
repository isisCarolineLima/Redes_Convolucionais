# Redes_Convolucionais  
Descrição do projeto: Implementação e Análise de Classificação com Redes Convolucionais e o dataset CUFS. O objetivo foi desenvolver uma rede convolucional capaz de classificar uma imagem de um rosto humano em feminino ou masculino. O modelo foi construído com 3 camadas convolucionais (ReLU e MaxPooling), uma camada Flatten, uma densa com 128 neurônios e uma de saída sigmoid para classificação binária. Foi treinado com otimizador Adam, função de perda binary_crossentropy, 20 épocas e batch size de 32. Após avaliar os resultados com os dados de teste, identificou-se overfitting. Tentativas de ajuste, como Early Stopping, pioraram o desempenho, e optou-se por manter o modelo original.  

Instalação: Não é necessário apenas abra o código no colab (arquivo .ipynb) e execute-o no seu dispositivo.  

Execução: Com o colab aberto execute bloco por bloco na ordem em que foram construidos. Não pule nenhum bloco, pois isso pode muito provavelmente causar um erro. Caso você faça isso, volte no primeiro bloco e comece tudo de novo dessa vez sem pular nenhum.  

Estrutura dos arquivos: O Relatorio_Tecnico_RedeConvolucional.pdf contém um relatório explicando, justificando e analisando o projeto. Já o Trabalho_em_dupla_Grupo_47_Rede_Convolucional.ipynb contém o colab do código do modelo de classificação desenvolvido pelo grupo.  

Tecnologias utilizadas: o projeto foi desenvolvido na linguagem de programação python, e utilizou como base as bibliotecas OS, CV2, Numpy(muito utilizada nos projetos de ciência de dados), tensorflow(usada no desenvolvimento do modelo) e matplotlib(para gerar os gráficos).  

Autores e Colaboradores(GRUPO 47):  
Isis Caroline Lima Viana  
Marco Antonio Oliveira Santos
