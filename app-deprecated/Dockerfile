FROM Python:3.13.3
ADD app.py .
ADD test.py .
ADD requirements.txt .
RUN pip install -r requirements.txt
CMD ["streamlit", "run", "app.py"]
