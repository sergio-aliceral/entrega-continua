# Objetivo
Integração contínua com Travis, cobertura de código com Jacoco/Codecov e entrega contínua com Heroku.

[![Build Status](https://travis-ci.com/sergio-aliceral/entrega-continua.svg?branch=master)](https://travis-ci.com/sergio-aliceral/entrega-continua)
[![codecov](https://codecov.io/gh/sergio-aliceral/entrega-continua/branch/master/graph/badge.svg?token=6ORBC9GJCJ)](https://codecov.io/gh/sergio-aliceral/entrega-continua)

## Iniciando

- `git clone https://github.com/sergio-aliceral/entrega-continua.git`
- `cd entrega-continua`

## Pré-requisitos
- `mvn --version`<br>

Você deverá ver a indicação da versão do Maven instalada e a versão do JDK. Observe que o JDK é obrigatório, assim como a definição das variáveis de ambiente **JAVA_HOME** e **M2_HOME**.

## Limpar, compilar e empacotar
- `mvn clean install`<br>

Gera arquivo _entrega-continua-1.0.0.jar_ no diretório _target_.

## Executando a aplicação
- `java -jar target/entrega-continua-1.0.0.jar`<br>

Executa o aplicativo por meio do arquivo jar criado pelo comando `mvn clean install`, conforme comentado anteriormente.

### Documentação

- http://localhost:9999/swagger-ui.html
- https://entrega-continua.herokuapp.com/swagger-ui.html
