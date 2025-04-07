# generative-insights
Insights sobre o reconhecimento de textos de IAs generativas. Feito para o bootcamp Decola Tech 2025, da Dio.

O OCR (Reconhecimento Óptico de Caracteres) é um dos recursos mais poderosos da inteligência artificial aplicada ao processamento de imagens. Com ele, é possível detectar texto presente em imagens, fotos ou documentos escaneados e convertê-los em dados editáveis.

## Como funciona o processo de OCR

1. Pré-processamento da imagem: Ajustes como contraste, nitidez e remoção de ruído aumentam a precisão do reconhecimento.
2. Detecção de áreas com texto: O sistema identifica blocos, linhas e palavras dentro da imagem.
3. Reconhecimento de caracteres: Os caracteres são comparados com padrões conhecidos usando redes neurais treinadas.
4. Pós-processamento: Correções linguísticas e de contexto são aplicadas para melhorar a qualidade do texto extraído.

# Por Exemplo:
Usei o seguinte prompt enquanto enviei simultneamente as imagens da pasta **/inputs**:
>"Separadamente, identique os textos presente nessas 3 imagens."

E esses foram os resultados que consegui:

![text-1](https://github.com/user-attachments/assets/ca98467f-e4f7-4b53-ac64-76ce438ca7b5)

---
![text-2](https://github.com/user-attachments/assets/1bb78e38-fa47-49e8-a33a-3b52629d2eae)

---
![text-3](https://github.com/user-attachments/assets/9fc33db4-42b5-49d6-be2e-0c8f901d7a65)


---

## O que esta tecnologia nos possibilita?

### Identificação de texto em múltiplas fontes na mesma imagem

OCR é capaz de identificar:
- Fontes diferentes (ex: texto manuscrito + impresso).
- Tamanhos e estilos variados (negrito, itálico, cursivo).
- Textos em ângulos diferentes ou até parcialmente visíveis.

### Aplicações práticas

- Digitalização de documentos físicos, tais como livros, recibos e contratos.
- Acessibilidade digital (leitores de tela para deficientes visuais).
- Extração de dados para BI e análises automatizadas.
- Análise de imagens em redes sociais, cartazes e outdoors.

