FROM python:3 AS builder

COPY requirements.txt .
RUN pip install --user -r requirements.txt

FROM python:3-slim AS runtime

WORKDIR /code

COPY --from=builder /root/.local/ /root/.local
COPY src/ .

ENV PATH=/root/.local:$PATH

CMD [ "python", "./server.py" ]