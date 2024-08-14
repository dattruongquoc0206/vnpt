from ubuntu
workdir /src
copy main.py ./
run apt update
run apt -y install python3

cmd ["python3", "main.py"] 