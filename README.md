# Natural ou Fake Natty? Como Vencer na Era das IAs Generativas

## 🚀 Introdução

> Woooow! Look at this 👀

Olá pessoal, Venilton da DIO aqui! Inspirado na hype _"Natty or Not"_ do fisiculturismo, este Lab da DIO te convida a conhecer o mundo das IAs Generativas, explorando o potencial dessas tendências tecnológicas incríveis!

## 🎯 Bora Pro Desafio!? Você Já Venceu 💪🤓

### Objetivos

1. **Explorar IAs Generativas**: Utilize essas tecnologias para criar conteúdos que sejam o mais realista possível. Seja criativo! Você pode produzir imagens, textos, áudios, vídeos ou combinações de tudo isso!
1. **Potfólio de Projetos**:
    1. Faça o "fork" deste repositório, criando uma cópia em seu GitHub pessoal;
    2. Edite seu README com os detalhes do seu projeto, siga nosso [Template](#template) (é só copiar, colar e preencher);
    3. Submeta o link do seu repositório na plataforma da DIO. Pronto, você acabou de fortalecer seu portfólio de projetos nos perfis do GitHub e DIO 🚀
1. **Efeito de Rede**: Compartilhe seus resultados nas redes sociais com a hashtag **#LabDIONattyOrNot**. Não esqueça de nos marcar: [DIO](https://www.linkedin.com/school/dio-makethechange) e [falvojr](https://www.linkedin.com/in/falvojr).

### Template

```markdown
# Título do Projeto Extremamente Aesthetic ;)
Imagem Real vs IA Natural ou Fake Natty

## 📒 Descrição
Verificaçao de uma imagem de uma planta criada pela IA, em comparacao com uma
foto de uma planta real, para analisar qual será a imagem REAL (Natural) e qual a imagem da  planta Gerada pela IA (Fake Netty)

## 🤖 Tecnologias Utilizadas
Liste as Liste as IAs Generativas e outras ferramentas usadas;
Chat GPT 4 - Para Analise da imagens
Leonard.AI - Para geraçao da imagem a serem analisada
Cloud 3 Sonet - Para analise das descricao e imagens 
AWS Stable Difusion Generativas e outras ferramentas usadas como Google Leanse GitHub.

## 🧐 Processo de Criação
Descreva como você criou o conteúdo

- Utilizou-se  o Google Leans para identificaçao da Planta Real
- Foi feito uma foto de uma planta Real via celular
- Foi descrito as caracteristicas da planta a ser analisada e iserida no prompt da IA
- Foi feita a geraçao da Imagem via IA da planta a ser verificada 
- Foi feito o Upload da da Foto da  imagem Real
- Descreveu-se no prompt da Ia, para ser feito a analise e retornar com percentual de acerto e código utilizado pela IA.

Códigos gerados pea IA em Python
###############################################################################################################################################################################
from PIL import Image
import numpy as np
import matplotlib.pyplot as plt

# Load the images
real_image_path = "/mnt/data/IMG_20240605_154953_1.jpg"
ai_image_path = "/mnt/data/Default_Dracaena_is_a_botanical_neem_belonging_to_the_Dracenac_2.jpg"

real_image = Image.open(real_image_path)
ai_image = Image.open(ai_image_path)

# Display the images side by side for visual comparison
fig, axs = plt.subplots(1, 2, figsize=(15, 10))

axs[0].imshow(real_image)
axs[0].set_title("Real Image")
axs[0].axis('off')

axs[1].imshow(ai_image)
axs[1].set_title("AI Generated Image")
axs[1].axis('off')

plt.show()

# Resizing the images to the same dimensions for accurate comparison
ai_image_resized = ai_image.resize(real_image.size)

# Convert images to numpy arrays for detailed comparison
real_image_array = np.array(real_image)
ai_image_array_resized = np.array(ai_image_resized)

# Calculate differences
difference = np.abs(real_image_array - ai_image_array_resized)
percent_difference = np.mean(difference) / 255 * 100

percent_difference
################################################################################################################################################################################# 🚀 Resultados
Apresente os resultados do seu projeto
Com base na análise visual e quantitativa, podemos afirmar que a primeira imagem (IMG_20240605_154953_1.jpg) é a real e a segunda imagem (Default_Dracaena_is_a_botanical_neem_belonging_to_the_Dracenac_2.jpg) é a gerada por inteligência artificial. O percentual de diferença de aproximadamente 42.12% reflete as diferenças significativas nas características visuais entre as duas imagens. ​

Após realizar a análise comparativa das duas imagens, aqui estão os resultados:

### Visualização das Imagens
- **Imagem 1**: (Real)
  - Características: Folhas variegadas com listras verdes e brancas/amareladas, vaso preto, fundo com azulejos.
  - Arquivo: `IMG_20240605_154953_1.jpg`
  
- **Imagem 2**: (Gerada por IA)
  - Características: Folhas totalmente verdes, vaso branco, fundo com parede de tijolos.
  - Arquivo: `Default_Dracaena_is_a_botanical_neem_belonging_to_the_Dracenac_2.jpg`

### Análise e Percentual de Diferença
Foi calculado o percentual de diferença entre as duas imagens usando a média das diferenças absolutas entre os pixels correspondentes das imagens redimensionadas. O percentual de diferença obtido é de aproximadamente **42.12%**.

### Código Utilizado
Abaixo está o código utilizado para carregar, comparar e calcular o percentual de diferença entre as imagens:

```python
from PIL import Image
import numpy as np
import matplotlib.pyplot as plt

# Load the images
real_image_path = "/mnt/data/IMG_20240605_154953_1.jpg"
ai_image_path = "/mnt/data/Default_Dracaena_is_a_botanical_neem_belonging_to_the_Dracenac_2.jpg"

real_image = Image.open(real_image_path)
ai_image = Image.open(ai_image_path)

# Display the images side by side for visual comparison
fig, axs = plt.subplots(1, 2, figsize=(15, 10))

axs[0].imshow(real_image)
axs[0].set_title("Real Image")
axs[0].axis('off')

axs[1].imshow(ai_image)
axs[1].set_title("AI Generated Image")
axs[1].axis('off')

plt.show()

# Resizing the images to the same dimensions for accurate comparison
ai_image_resized = ai_image.resize(real_image.size)

# Convert images to numpy arrays for detailed comparison
real_image_array = np.array(real_image)
ai_image_array_resized = np.array(ai_image_resized)

# Calculate differences
difference = np.abs(real_image_array - ai_image_array_resized)
percent_difference = np.mean(difference) / 255 * 100

percent_difference
```

### Conclusão

Com base na análise visual e quantitativa, podemos afirmar que a primeira imagem (`IMG_20240605_154953_1.jpg`) é a real e a segunda imagem (`Default_Dracaena_is_a_botanical_neem_belonging_to_the_Dracenac_2.jpg`) é a gerada por inteligência artificial. 

O percentual de diferença de aproximadamente 42.12% reflete as diferenças significativas nas características visuais entre as duas imagens.

## 💭 Reflexão (Opcional)
Comente sobre o desafio de criar algo 'natty' com IA.
O desafio é extremamente desafiador, pois envolve várias etapas e escolhas das ferramentas a serem uilizadas,
Isso me deixou bastante curioso como as IA's fariam todo processo, reflentindo sobre este processo,penso 
o quanto evoluimos,e ainda sera toda essa evolucao de IA's, pois em um processo antes dessas I'As seria gasto  um tempo considerável de análise e processamento, 
e tudo isso foi executado em muito pouco tempo.
 Fica aqui minha  reflexao,  quais serao os proximos recursos que as Ia's ganharao em um futuro próximo e como lidaremos com essas IA's ?

```

### Exemplos e Insigths

- [E-BOOK](/exemplos/E-BOOK.md)
- [Podcast](/exemplos/PODCAST.md)
- [Vídeo (Avatar Virtual)](/exemplos/VIDEO.md)

## Links Interessantes

[Base10: If You’re Not First, You’re Last: How AI Becomes Mission Critical](https://base10.vc/post/generative-ai-mission-critical/)

![Base10's Trend Map Generative AI](https://github.com/digitalinnovationone/lab-natty-or-not/assets/730492/f4df26e8-f8f7-4419-8252-c69d73ea930c)
