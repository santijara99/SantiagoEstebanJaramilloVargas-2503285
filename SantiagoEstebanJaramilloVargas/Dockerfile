FROM nginx:latest
RUN mkdir /SantiagoEstebanJaramilloVargas-2503285
RUN chmod -R 777 /SantiagoEstebanJaramilloVargas-2503285
COPY recursos/img7.jpg /SantiagoEstebanJaramilloVargas-2503285
COPY main.sh /SantiagoEstebanJaramilloVargas-2503285
RUN chmod +x /SantiagoEstebanJaramilloVargas-2503285/main.sh
RUN cd /SantiagoEstebanJaramilloVargas-2503285
RUN  /SantiagoEstebanJaramilloVargas-2503285/main.sh
COPY 7/template7 /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]