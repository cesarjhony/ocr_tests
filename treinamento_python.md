## Treinar com rótulos

- Prepare os arquivos para serem treinados disponibilizando-os em um link público

- Envie os arquivos para serem treinados
https://docs.microsoft.com/pt-br/azure/cognitive-services/form-recognizer/quickstarts/python-labeled-data?tabs=v2-0
https://westus2.dev.cognitive.microsoft.com/docs/services/form-recognizer-api-v2/operations/AnalyzeLayoutAsync

- Receber a resposta asyncrona
https://westus2.dev.cognitive.microsoft.com/docs/services/form-recognizer-api-v2/operations/GetAnalyzeLayoutResult
Copiar dados do json para um arquivo na mesma pasta da imagem com o nome "imagem.jpg.ocr.json" onde imagem.jpg é o nome da imagem

- Salvar todos arquivos de treino, imagens e ...ocr.json no armazenamento azure, com azure explorer em um "blob cointeiner"

- Rotular manualmente
  https://docs.microsoft.com/pt-br/azure/cognitive-services/form-recognizer/quickstarts/label-tool?tabs=v2-0
  https://fott.azurewebsites.net/

- Salvar o nome do id do modelo ao final do treinamento

  no caso: 0374c87b-d98b-4686-8300-856ba3540eb3 

## Obter dados de uma imagem

- Prerequisitos:

  - modelo de treinamento
  - endpoint e chave

- Obter analise de uma imgem 

  https://docs.microsoft.com/pt-br/azure/cognitive-services/form-recognizer/quickstarts/python-train-extract?tabs=v2-0#analyze-forms-for-key-value-pairs-and-tables