<div align="center">

# Pós Tech FIAP - Hackathon - Grupo 12

![GitHub Release Date](https://img.shields.io/badge/Release%20Date-Abril%202025-yellowgreen)
![](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellowgreen)
<br>
![](https://img.shields.io/badge/Version-%20v1.0.0-brightgreen)
</div>

### 👨‍💼👩‍💼‍ Autores

Este é um projeto que está em construção pelos desenvolvedores:

![](https://img.shields.io/badge/RM357321-Alexandre%20Miranda-blue)
<br>
![](https://img.shields.io/badge/RM357437-Diego%20Ceccon-blue)
<br>
![](https://img.shields.io/badge/RM357218-Jéssica%20Rodrigues%20-blue)
<br>
![](https://img.shields.io/badge/RM358002-Rodrigo%20Sartori-blue)
<br>
![](https://img.shields.io/badge/RM357991-Wilton%20Souza%20-blue)

### ⚠️ Problema

<p align="justify">
A empresa FIAP X contratou a equipe para melhorar um projeto de processamento de imagens. Esse projeto pega um vídeo, extrai as imagens dele e gera um arquivo .zip. A ideia foi apresentada para investidores, que gostaram bastante e agora querem uma versão onde seja possível enviar um vídeo e depois fazer o download do arquivo gerado.
Atualmente, o projeto não segue boas práticas de arquitetura de software. Por isso, o desafio será desenvolver uma nova versão da aplicação usando os conhecimentos aprendidos no curso, como organização da arquitetura, uso de microsserviços, qualidade de software, mensageria, entre outros.
</p>

## 🎥 Vídeo de apresentação

Para assistir ao vídeo de apresentação do projeto, que contém:
- A descrição detalhada do problema
- Arquitetura utilizada no projeto
- Solução de infraestrutura proposta
- Demonstração da aplicação em funcionamento

basta acessar o link: [Apresentação no Youtube]()

### Repositório

Repositório que compõem a aplicação e a infraestrutura.

Ordem de execução: 
1. **[VPC](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-vpc)**: Contém os arquivos terraform de criação da VPC.
2. **[BD](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-db)**: Contém os arquivos terraform de criação dos Bancos de Dados no RDS.
3. **[Queue](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-queue)**: Contém os arquivos terraform de criação das filas usando o SQS.
4. **[K8S - Cluster](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-k8s-cluster)**: Contém os arquivos terraform de criação do Cluster da aplicação.
5. **[K8S - Infra](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-k8s-infra)**: Contém os arquivos terraform de criação da Infraestrutura da aplicação.
6. **[Observability](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-observability)**: Contém os arquivos terraform de criação dos recursos de observação da aplicação.
7. **[Lambda Receive Video](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-lambda-video-receive)**: Contém os arquivos terraform de criação da Lambda Receive que recebe o video e manda para o processamento.
8. **[Lambda Authorizer](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-lambda-authorizer)**: Contém os arquivos terraform de criação da Lambda Authorize.
9. **[Cognito](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-cognito)**: Contém os arquivos terraform de criação do Cognito.
10. **[Gateway](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-api-gateway)**: Contém os arquivos terraform de criação da API Gateway.
11. **[Mail](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-mail)**: Contém os arquivos terraform de criação de Mail, responsável por enviar o email após o processamento do video e do ECR da aplicação.
12. **[Process](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-process)**: Contém os arquivos terraform de criação de Process, responsável pelo processamento do video e do ECR da aplicação.
13. **[Video API - Orquestrador](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-video)**: Contém os arquivos terraform de criação da Video API (Orquestrador) e do ECR da aplicação.
14. **[Frontend - Alquimia Frames](https://github.com/hackathon-fiap-soat-12/fiap-hackathon-frontend)**: Contém os arquivos terraform de criação do front-end da aplicação.
