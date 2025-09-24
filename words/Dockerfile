# words

# C'est un serveur API REST en Java. Il se compile avec maven.

FROM ubuntu
# Sur une distribution Debian/Ubuntu, on peut installer Java et maven comme suit :

RUN apt-get install maven

# Voici la commande qui permet d'invoquer maven pour compiler le programme :
COPY . .
RUN mvn verify

#Le résultat est un fichier appelé words.jar placé dans le répertoire target.

#Le serveur se lance ensuite avec la commande suivante :

CMD java -Xmx8m -Xms8m -jar words.jar

# (En se plaçant dans le répertoire où se trouve words.jar.)
