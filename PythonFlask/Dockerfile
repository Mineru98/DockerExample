FROM python
COPY ./Urlhit /server
WORKDIR /server
RUN pip install Flask==1.1.0
EXPOSE 5000
CMD ["python", "server.py"]