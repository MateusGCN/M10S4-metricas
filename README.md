# Ponderada Criando métricas

## pré requisito

- dot net 8
- jetbrains rider
- dotnet-counters

### Para instalar o dotnet-counters:
``` dotnet tool install --global dotnet-counters ```

## Criar uma métrica personalizada

### Criando um projeto utilizando o:
``` dotnet new console ```

![image](./images/image1.png)

### Instalando o pacote  NuGet System.Diagnostics.DiagnosticSource:

![image](./images/image2.png)

### Atualizando o Program.cs:

![image](./images/image3.png)

### Rodando o Projeto:

![image](./images/image4.png)

### Coletando as métricas:

![image](./images/image5.png)


##  Obtenha um Medidor por meio da injeção de dependência

### Rodando o projeto com as mudanças para API:

![image](./images/image6.png)

### Testando a API utilizando o Postman:

![image](./images/image7.png)
