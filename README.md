# dio-transcri-o-texto-imagem
Projeto proposto no Bootcamp Bradesco da DIO. Análise do comportamento de duas tecnologias a analisar imagens.

# Comparação entre OCR e OpenAI GPT-4 Multimodal

## Visão Geral

Este projeto compara dois métodos de extração e processamento de texto a partir de imagens: o *OCR (Reconhecimento Óptico de Caracteres)* e o modelo *GPT-4 Multimodal da OpenAI. A análise foi feita com o objetivo de entender como cada abordagem lida com diferentes tipos de conteúdo, como **placas de veículos* e textos simples de livros.

O trabalho é dividido em duas análises:

1. *Documento Pessoal*: Avaliação de ambos os métodos na transcrição de informações de um documento.
2. *Análise de Identificação de Placas de Veículos*: Comparação de como os dois sistemas identificam elementos visuais, como placas de veículos.

### Tecnologias Usadas

- *OCR* (Reconhecimento Óptico de Caracteres): Utilizado para extrair texto de imagens. Ferramentas como *Tesseract OCR* foram usadas para essa tarefa.
- *OpenAI GPT-4 Multimodal*: Modelo capaz de processar imagens e texto simultaneamente, realizando tarefas como compreensão de texto visual (plano de fundo) e análise contextual.

---

## 1. Análise de Documento Pessoal

### OCR

O OCR foi utilizado para transcrever um *documento pessoal* (como uma carta ou contrato). Ele fez uma boa transcrição, mas teve dificuldades quando o documento continha *textos manuscritos* ou *fontes danificadas*. No geral o resultado é confuso e desorganizado.

![Imagem do WhatsApp de 2025-03-18 à(s) 15 38 24_59f806a5](https://github.com/user-attachments/assets/425426b9-e7dd-4111-ab9f-37fb055666e9)


### OpenAI GPT-4 Multimodal

O GPT-4 multimodal *não realizou a transcrição de textos diretamente da imagem*. Por conter informações pessoais a IA não se permitiu gerar a transcrição.

![image](https://github.com/user-attachments/assets/b596ee96-38cf-401d-a955-7f43353e259f)

---

## 2. Transcrição de placas de veículos

### OCR

O OCR consegue identificar o texto em *placas de veículos* mas com dificuldade por conta da diferença de qualidade entre as imagens, as cores do fundo e posicionamento das letras. Resultado :

![Imagem do WhatsApp de 2025-03-18 à(s) 15 36 44_64324c0b](https://github.com/user-attachments/assets/84633cca-c6d8-4e32-bc8f-3f9a60a3c0a0)


### OpenAI GPT-4 Multimodal

O modelo multimodal da OpenAI, por sua vez conseguiu gerar uma transcrição precisa e organizada das informações.

![Imagem do WhatsApp de 2025-03-18 à(s) 15 37 04_2427b171](https://github.com/user-attachments/assets/04e457fd-df17-4ca1-9fe8-1708d3dd6937)

---


## Comparação Geral

| *Critério*                         | *OCR*                                               | *OpenAI GPT-4 Multimodal*                                     |
|-------------------------------------|-----------------------------------------------------|--------------------------------------------------------------|
| *Extração de Texto*                | Preciso, mas depende da qualidade da imagem.        | Realiza extração direta de texto com alta precisão, processando texto e contexto visual simultaneamente. |
| *Identificação de Placas de Veículos* | Identifica texto, mas com limitações.               | Realiza a extração de texto e interpreta o contexto visual das placas, com maior entendimento contextual. |
| *Análise de Documento Pessoal*     | Boa transcrição, mas com dificuldades em fontes manuscritas ou danificadas. | Não realiza transcrição direta de documentos pessoais, mas pode processar e analisar textos extraídos previamente. |

---

## Insights

Durante o desenvolvimento deste projeto, foram adquiridos diversos insights valiosos sobre as tecnologias envolvidas:

1. **OCR**: Eficaz na transcrição de texto, mas depende da qualidade da imagem e da clareza da fonte. Imagens de baixa qualidade ou fontes manuscritas podem causar erros significativos.

2. **GPT-4 Multimodal**: Realiza extração de texto diretamente de imagens e também pode interpretar e analisar o texto extraído. Além disso, oferece uma análise mais sofisticada, entendendo o contexto visual e gerando insights mais profundos a partir do texto extraído.

3. **Identificação de Placas de Veículos**: O OCR pode extrair texto das placas, mas o GPT-4 é mais eficaz ao entender o contexto das placas e fornecer uma interpretação precisa do significado por trás do texto extraído.

4. **Textos Comuns**: O OCR é eficiente para textos simples, mas o GPT-4 se destaca em textos complexos, podendo fornecer resumos e análises mais detalhadas.

5. **Limitações**: Tanto o OCR quanto o GPT-4 podem ter dificuldades com imagens de baixa qualidade. O OCR precisa de uma boa imagem para uma extração precisa, enquanto o GPT-4 precisa de texto de boa qualidade extraído de imagens para análise eficaz.
