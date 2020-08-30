FROM nginx:latest
LABEL maintaner 'Aluno Diego Martinez <Diego Martinez at curso docker>'

## Cria o arquivo conteudo.hmtl
RUN echo '<h1>Sem conteudo</h1>' > /usr/share;nginx/html/conteudo.html
## Copia os arquivos do host para dentro do container.
COPY *.html /usr/shar/nginx/html