# web
# C'est un serveur web en Go. Pour compiler du Go, on peut utiliser l'image golang, ou bien installer les paquetages Go dans n'importe quelle image de base.

FROM golang

# Tout le code est contenu dans un fichier source unique (dispatcher.go), et se compile de la manière suivante :

COPY dispatcher.go .
RUN go build dispatcher.go

# Cela produit un exécutable appelé dispatcher, qui se lance comme suit :

CMD ["./dispatcher"]
# Listening on port 80
