from google.colab import drive
from rembg import remove
from PIL import Image

# Montar o Google Drive
drive.mount('/content/drive')

# Definir o caminho da imagem de entrada e saída no Google Drive
input_path = '/content/drive/My Drive/Imagem/primeiro-plano.jpg'
output_path = '/content/drive/My Drive/Imagem/semfundo.png'

# Abrindo a imagem de entrada
image = Image.open(input_path)

# Removendo o fundo da imagem
output = remove(image)

# Salvando a imagem de saída
output.save(output_path)

print(f"Imagem salva em {output_path}.")
