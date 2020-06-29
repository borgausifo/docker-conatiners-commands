FROM python:3
WORKDIR /app
COPY hello.py .
COPY start-app.sh .
RUN pip install Flask
CMD ["/bin/bash", "start-app.sh"]