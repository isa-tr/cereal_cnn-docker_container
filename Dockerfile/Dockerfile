FROM jjanzic/docker-python3-opencv
RUN echo "imagen bajada" && apt-get update && apt-get -y update && apt-get install -y python3-pip && pip3 -q install pip --upgrade

COPY container .
RUN echo "copiado con éxito" && pip3 install jupyter && echo "jupyter installed" && pip3 install -r requirements.txt

CMD ["jupyter", "notebook", "--port=8888", "--no-browser", "--ip=0.0.0.0", "--allow-root"]
