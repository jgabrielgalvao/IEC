FROM python:3 
#FROM python:3 cria uma imagem python na versão 3, especificada

WORKDIR /app
#WORDKIR /app, cria uma pasta na raiz '/' que se chama app

COPY . .
#COPY origem (arquivo requirements em app_imc_python) destino (arquivo que sera criado dentro da pasta app)
# . ., copia todos os arquivos e os insere no local de destino (no caso, a pasta app)

RUN pip install -r requirements.txt
#RUN, este comando executa um comando no momento de criação da imagem
#pip install -r requirements.txt comando em python para instalar todas as dependencias presentes no arquivo requirements.txt

CMD ["python", "imc.py"]
#CMD, essa é uma execução de comando no momento em que o container é iniciado
#["python", "imc.py"], aqui é o comando python imc.py, iniciando a aplicação

EXPOSE 80
#EXPOSE, comando para especificar a porta que será utilizada
