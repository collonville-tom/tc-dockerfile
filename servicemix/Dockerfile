FROM openjdk:8-jre-alpine

RUN wget http://apache.crihan.fr/dist/servicemix/servicemix-7/7.0.1/apache-servicemix-7.0.1.zip \
&& unzip apache-servicemix-7.0.1.zip && rm apache-servicemix-7.0.1.zip

COPY . /
CMD cd /apache-servicemix-7.0.1/bin; ./servicemix