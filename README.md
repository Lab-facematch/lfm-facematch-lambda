# Facematch

## Passos:
- Verifica se a imagem existe no bucket /documents
- Indexa a imagem do bucket /documents no Rekognition
- Analisa a imagem do bucket /photos no Rekognition
- Processa o resultado da análise
- Envia o resultado da análise por SNS para o user-service
- Limpar a coleção de Rekognition