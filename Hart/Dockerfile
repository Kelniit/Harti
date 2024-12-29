FROM tensorflow/serving

COPY /HartModule /ModelFolder/1

EXPOSE 8501

CMD ["tensorflow_model_server", \
    "--rest_api_port=8501", \
    "--model_name=HartModule", \ 
    "--model_base_path=/ModelFolder"]