# Desafio: Criação de Base de Dados e Treinamento da Rede YOLO

## Descrição do Projeto

Neste projeto, vamos rotular uma base de dados e aplicar o treinamento com a rede YOLO. O objetivo é criar uma base de dados personalizada e treinar a rede YOLO para detectar pelo menos duas novas classes, além das classes já previamente treinadas.

---

### Etapas do Projeto

1. **Rotular as Imagens**  
   Utilize o software [LabelMe](http://labelme.csail.mit.edu/Release3.0/) para rotular as imagens. O software permite criar anotações para identificar objetos nas imagens.

2. **Treinamento com a Rede YOLO**  
   A rede YOLO pode ser acessada e configurada a partir do repositório oficial: [YOLO - Darknet](https://pjreddie.com/darknet/yolo/).

3. **Utilização de Dados Pré-Rotulados (Opcional)**  
   Para quem preferir não criar anotações do zero, é possível utilizar as imagens rotuladas disponíveis no conjunto de dados [COCO](https://cocodataset.org/#home).

4. **Transfer Learning no Google Colab**  
   Caso o seu computador não consiga rodar a rede YOLO localmente, o treinamento pode ser realizado no Google Colab. Um exemplo de implementação está disponível neste link:  
   [Transfer Learning no Colab](https://colab.research.google.com/drive/1lTGZsfMaGUpBG4inDIQwIJVW476ibXk_#scrollTo=j0t221djS1Gk).

---

### Requisitos do Trabalho

- O trabalho deve conter **pelo menos duas classes retreinadas** para detecção.
- As classes já treinadas previamente também devem ser consideradas durante o treinamento.
- O resultado esperado é uma detecção semelhante ao exemplo mostrado na imagem a seguir:

#### Exemplo de Resultado Esperado

Figura 1: Detecção em imagens com a rede YOLO.

---

### Recursos Adicionais

Os slides utilizados nas aulas estão disponíveis para consulta:  
[Apresentação Completa](#) (Substitua com o link correto, caso disponível)

---

### Ferramentas Utilizadas

- [LabelMe](http://labelme.csail.mit.edu/Release3.0/) - Para rotulagem das imagens.
- [YOLO - Darknet](https://pjreddie.com/darknet/yolo/) - Para treinamento e detecção de objetos.
- [COCO Dataset](https://public.roboflow.com/object-detection/pascal-voc-2012/1) - Para uso de dados pré-rotulados (opcional).
- [Google Colab](https://colab.research.google.com/) - Para realizar o treinamento utilizando transfer learning (opcional).

---
