# 🚗 Desafio Fundamentos - Sistema de Estacionamento

Aplicação de console desenvolvida em **C# (.NET)** que simula o funcionamento de um estacionamento.  
O sistema permite **adicionar, remover e listar veículos**, calculando automaticamente o valor a pagar com base no tempo estacionado.

---

## 📋 Sumário
- [Visão Geral](#-visão-geral)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Funcionalidades](#-funcionalidades)
- [Como Executar](#-como-executar)
- [Exemplo de Execução](#-exemplo-de-execução)
- [Autor](#-autor)

---

## 🚀 Visão Geral

Este projeto foi desenvolvido como parte do **Desafio de Fundamentos em C# (DIO Bootcamp)**.  
Ele demonstra o uso de **classes, listas, laços, condicionais e entrada/saída de dados** no console.

O sistema solicita os preços iniciais, apresenta um menu interativo e realiza as operações sobre os veículos cadastrados.

---

## 🧩 Estrutura do Projeto

```
DesafioFundamentos/
├── Program.cs
└── Models/
    └── Estacionamento.cs
```

### 📄 Program.cs
Gerencia o **menu principal** e as interações com o usuário.

### 📄 Models/Estacionamento.cs
Contém toda a **lógica de negócio**:
- Armazenamento de veículos (`List<string>`)
- Cálculo do valor total
- Validação de entrada

---

## ⚙️ Funcionalidades

### 🚘 1. Cadastrar Veículo
Solicita a placa e adiciona o veículo ao estacionamento.

```
Digite a placa do veículo para estacionar:
ABC1234
Veículo com a placa ABC1234 cadastrado com sucesso!
```

---

### ❌ 2. Remover Veículo
Solicita a placa, o número de horas e calcula o valor total a pagar.

```
Digite a placa do veículo para remover:
ABC1234
Digite a quantidade de horas que o veículo permaneceu estacionado:
3
O veículo ABC1234 foi removido e o preço total foi de: R$ 25,00
```

🧮 **Fórmula do cálculo:**
```
valorTotal = precoInicial + (precoPorHora * horas)
```

---

### 📋 3. Listar Veículos
Mostra todos os veículos atualmente estacionados.

```
Os veículos estacionados são:
ABC1234
XYZ9876
```

Se não houver veículos:
```
Não há veículos estacionados.
```

---

### 🏁 4. Encerrar
Finaliza o programa exibindo a mensagem:

```
O programa se encerrou
```

---

## 🧠 Como Executar

### ✅ Pré-requisitos
- [.NET SDK 6.0 ou superior](https://dotnet.microsoft.com/download/dotnet/6.0)

### ▶️ Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/DesafioFundamentos.git
   cd DesafioFundamentos
   ```

2. Compile e execute:
   ```bash
   dotnet run
   ```

3. Siga as instruções exibidas no terminal:
   ```
   Seja bem vindo ao sistema de estacionamento!
   Digite o preço inicial:
   5
   Agora digite o preço por hora:
   2
   ```

---

## 💡 Exemplo de Execução

```
Seja bem vindo ao sistema de estacionamento!
Digite o preço inicial:
5
Agora digite o preço por hora:
2

Digite a sua opção:
1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar
> 1

Digite a placa do veículo para estacionar:
ABC1234
Veículo com a placa ABC1234 cadastrado com sucesso!

Pressione uma tecla para continuar...
```

---

## 👨‍💻 Autor

Desenvolvido como parte do **Desafio de Fundamentos em C# - DIO Bootcamp**  
📅 Versão: 1.0  
📄 Licença: MIT  

**Autor:** _Seu Nome Aqui_

---

🧱 **Tecnologias utilizadas:**
- .NET 6.0  
- C#  
- Programação orientada a objetos  
- Console Application  

---
