# Projeto Fase 6 - Comparativo de Modelos de Visão Computacional: YOLO vs. CNN

## 📄 Descrição do Projeto

Este repositório contém a solução para a **Fase 6 do PBL de Inteligência Artificial & Computer Systems**. O objetivo deste projeto foi explorar, implementar e avaliar criticamente diferentes abordagens de visão computacional para um problema de reconhecimento de objetos customizado: a identificação de controles de PlayStation 5 e controles de TV.

Três modelos foram desenvolvidos e comparados:
1.  **YOLOv5 Adaptável:** Um modelo de detecção de objetos de última geração, treinado com nosso próprio dataset.
2.  **YOLOv5 Padrão:** O modelo YOLOv5 pré-treinado, usado como base de comparação.
3.  **CNN de Classificação:** Uma Rede Neural Convolucional construída do zero com TensorFlow/Keras para classificar as imagens.

Toda a implementação, análise de resultados, gráficos comparativos e conclusões detalhadas estão documentadas no notebook Jupyter (`.ipynb`) presente neste repositório.

---

## 🚀 Tecnologias Utilizadas

* Python 3
* Google Colab / Jupyter Notebook
* YOLOv5 (Ultralytics)
* TensorFlow / Keras
* Pandas & NumPy
* Matplotlib
* Google Drive (para armazenamento do dataset)

---

## 🛠️ Como Executar o Projeto

Para replicar os resultados e explorar o código, siga os passos abaixo:

1.  **Clone este repositório:**
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO_AQUI]
    ```

2.  **Prepare o Dataset:** O dataset utilizado (imagens e rótulos) precisa ser carregado no seu Google Drive, seguindo a estrutura de pastas detalhada no início do notebook.
    * Para ter acesso ao dataset utilizado pelo grupo basta acessar os links abaixo: 
    Modelo YOLO: https://drive.google.com/drive/folders/15Okr7FbYQg_MqNde5KL9UoTZOSVPFUWk?usp=sharing
    Modelo CNN: https://drive.google.com/drive/folders/15Okr7FbYQg_MqNde5KL9UoTZOSVPFUWk?usp=sharing

4.  **Abra no Google Colab:** Faça o upload do arquivo `.ipynb` para o Google Colab.

5.  **Execute as Células:** Execute as células do notebook em ordem. O código irá instalar as dependências, conectar ao seu Google Drive, treinar os modelos e realizar as avaliações.

---

## 📺 Demonstração em Vídeo

Uma demonstração do funcionamento do projeto, incluindo o teste do modelo treinado em novas imagens, está disponível no YouTube.

**[➡️ Assista ao vídeo de demonstração aqui](https://youtu.be/muM-ONB5ZMI)**

---

## 📊 Resultados e Conclusões

A análise comparativa completa, avaliando critérios como precisão, tempo de treinamento, facilidade de uso e capacidade de cada modelo, encontra-se na seção final do notebook.

A conclusão indicou que, para a tarefa de classificação de imagens com um único objeto, a **CNN treinada do zero** ofereceu o melhor equilíbrio entre performance e simplicidade. Para a tarefa mais complexa de detecção e localização, a **YOLO Adaptável** se mostrou promissora, embora exija um dataset mais robusto para atingir uma precisão ideal.

Para observar as imagens de testes preditas pelos modelos YOLO basta abrir as imagens com o nome  "YOLO padrão" para o modelo YOLO padrão e "YOLO adaptável" para o modelo YOLO adaptável, ou caso preferir as imagens estarão também no Drive compartilhado acima, e para observar os testes preditos pela CNN basta abrir o Colab e executar as células de código. O

---

## 👨‍💻 Autor

* **Nome:** `Bernardo Zandoná Rupolo`
* **RM:** `RM 565182`

*Projeto desenvolvido para a disciplina de Inteligência Artificial da FIAP.*
