# CI/CD
Document expliquant les processus de d'integration et déployement continu


## Les Builds

### Le front

**dev** : à chaque commit un build est effectué par github action et posté sur docker hub

**master:** à chaque release un build est effectué par github action et posté sur docker hub

## Le back

**dev** : à chaque commit un build est effectué par github action et posté sur docker hub

**master** : à chaque commit un build est effectué par github action et posté sur docker hub

Les builds sont push sur [Docker Hub](https://hub.docker.com/u/erasme)

- [Le Back](https://hub.docker.com/r/erasme/datatlas-back)
- [Le Front](https://hub.docker.com/r/erasme/datatlas-front)

D'autres build du front datatlas existent sur Docker Hub mais ont vocation à être supprimées ne pouvant servir qu'a des usages spécifiques