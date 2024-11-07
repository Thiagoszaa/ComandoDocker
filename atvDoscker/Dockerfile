# Usa uma imagem base com Python
FROM python:3

# Define o diretório de trabalho
WORKDIR /app

# Copia os arquivos para o contêiner
COPY . .

# Instala as dependências necessárias
RUN pip install flask

# Comando para rodar a aplicação
CMD ["python", "app/main.py"]
