FROM python:3.12
EXPOSE 5000
WORKDIR /app
RUN pip install Flask Flask-SQLAlchemy flask-cors flask-bcrypt flask-jwt-extended Flask-Migrate psycopg2-binary python-dotenv
COPY . .
CMD ["flask", "run", "--host", "0.0.0.0"]