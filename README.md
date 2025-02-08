# CI/CD Aplicação no GitLab com GCP

Desafio do curso Formação Kubernetes Fundamentals onde é realizado o deploy de uma aplicação PHP com banco de dados MySql utilizando docker para gerar o build das imagens em um cluster Kubernetes. Com o GitLab é feito a configuração para realizar a etapa de integração contínua e posteriormente o deploy contínuo no GKE do Google Cloud Computer(GCP).


## Stack utilizada

- Kubernetes
- Docker
- PHP
- MySql
- GitLab CI/CD
- GCP Cloud

## Licença

[MIT](https://choosealicense.com/licenses/mit/)

# Kubernetes CI/CD DIO Challenge

Este projeto faz parte do desafio da Digital Innovation One (DIO) sobre integração e entrega contínua (CI/CD) em um ambiente Kubernetes, onde é realizado o deploy de uma aplicação PHP com banco de dados MySQL, utilizando Docker para gerar o build das imagens em um cluster Kubernetes. Com o GitLab, é feita a configuração para realizar a etapa de integração contínua e, posteriormente, o deploy contínuo no GKE do Google Cloud Platform (GCP).

## Objetivo

Automatizar o processo de build, testes e deploy de uma aplicação dentro de um cluster Kubernetes, utilizando pipelines de CI/CD.

## Tecnologias Utilizadas

- Kubernetes
- Docker
- Helm
- Jenkins/GitHub Actions
- YAML

## Requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- Docker
- Minikube ou um cluster Kubernetes
- Kubectl
- Helm
- Jenkins ou GitHub Actions configurado

## Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/victorfg21/kubernetes-cicd-dio-challenge.git
   cd kubernetes-cicd-dio-challenge
   ```

2. **Inicie o Minikube (caso esteja utilizando):**
   ```bash
   minikube start
   ```

3. **Aplique os manifests Kubernetes:**
   ```bash
   kubectl apply -f manifests/
   ```

4. **Configure o pipeline de CI/CD no Jenkins/GitHub Actions conforme a documentação fornecida.**

5. **Verifique os recursos implantados:**
   ```bash
   kubectl get all
   ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
