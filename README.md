# Instalación de minicube y kubectl

## Minicube
Siguiendo los pasos de la [pagina oficial](https://minikube.sigs.k8s.io/docs/start/), realizaremos los siguientes comandos:

```
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64

sudo install minikube-linux-amd64 /usr/local/bin/minikube

minikube start
```

![Captura de pantalla de 2022-05-24 22-36-20](https://user-images.githubusercontent.com/91556405/170127533-07e5523c-a402-40e7-a384-1985a670256f.png)


## Kubectl
Al igual que con minicube, seguimos los pasos de la [pagina oficial](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/) y realizaremos los siguientes comandos:

```
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"

sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl

kubectl version --client
```

![Captura de pantalla de 2022-05-24 22-20-51](https://user-images.githubusercontent.com/91556405/170126017-cfb49eb3-f4f5-4f25-b79c-41a418bd6436.png)
![Captura de pantalla de 2022-05-24 22-21-20](https://user-images.githubusercontent.com/91556405/170126414-f8ac3b44-7adb-467a-a7bb-f2d835211b81.png)
