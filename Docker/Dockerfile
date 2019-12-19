FROM ubuntu:latest
RUN apt-get update && apt-get install -y python3 python3-pip
RUN apt-get update && apt-get install -y git
RUN mkdir src
WORKDIR src/
ARG aaby4373
ARG Ihaveadream1#

RUN git clone https://${username}:${password}@github.com/aaby4373/TVCA.git
RUN pip3 install jupyter
RUN pip3 install matplotlib
RUN pip3 install pandas
RUN pip3 install simpledbf==0.2.0
RUN pip3 install seaborn
RUN pip3 install glob2
RUN pip3 install DateTime
RUN pip3 install numpy
RUN pip3 install scikit-learn
RUN pip3 install statsmodels
RUN pip3 install scikit-image
RUN pip3 install scikit-plot
RUN pip3 install calendra

RUN python3
ENTRYPOINT ["jupyter", "notebook","--ip=*", "--allow-root"]



