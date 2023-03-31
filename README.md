## Documentação em desenvolvimento

OCR em Python com Pytesseract

Este projeto utiliza a biblioteca Pytesseract juntamente com outras bibliotecas auxiliares para realizar a leitura e extração de texto em arquivos PDF. O script converte as páginas do arquivo PDF em imagens JPG e, em seguida, utiliza a biblioteca Pytesseract para extrair o texto dessas imagens.

Dependências
As seguintes bibliotecas são necessárias para executar o script:

pytesseract
numpy
cv2
cv2_imshow
re
imageio
PIL
os
pandas
pdf2image

Instalação
Para instalar todas as dependências necessárias, execute o seguinte comando:

Copy code
pip install pytesseract numpy opencv-python cv2_imshow regex imageio Pillow os pandas pdf2image

Limitações
Este projeto foi desenvolvido para arquivos PDF com texto em língua portuguesa. Para arquivos em outros idiomas, pode ser necessário ajustar os parâmetros do Pytesseract. Além disso, a qualidade do OCR pode variar de acordo com a qualidade das imagens e a complexidade do layout do arquivo PDF.

Contribuições
Contribuições são bem-vindas! Se você encontrar um problema ou tiver alguma sugestão de melhoria, por favor, abra uma issue ou um pull request.
