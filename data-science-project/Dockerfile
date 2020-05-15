FROM continuumio/miniconda3 
WORKDIR /app
RUN conda install numpy pandas seaborn jupyter
EXPOSE 8888
VOLUME /app
CMD ["jupyter" , "notebook" , "--ip='*'" , "--port=8888" , "--no-browser" , "--allow-root"]
