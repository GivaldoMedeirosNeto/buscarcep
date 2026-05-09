# 📮 BuscarCEP

Sistema desenvolvido em Java para consulta de CEP utilizando WebServices externos, oferecendo versões Desktop com JavaFX e Console.

---

## 🚀 Objetivo

O projeto foi criado com o intuito de facilitar consultas de endereços através de CEPs brasileiros utilizando integração com APIs públicas como ViaCep e República Virtual.

A aplicação possui duas versões:
- Interface gráfica utilizando JavaFX
- Aplicação via Console

---

## 🛠️ Tecnologias Utilizadas

- Java
- JavaFX
- API ViaCep
- API República Virtual
- JSON
- XML

---

## ✨ Funcionalidades

- Consulta de CEP em tempo real
- Integração com WebServices externos
- Exibição de:
  - Logradouro
  - Bairro
  - Cidade
  - Estado
  - Complemento
- Interface gráfica amigável
- Versão Console para testes rápidos
- Suporte a retorno JSON e XML

---

## 🌐 WebServices Utilizados

### ViaCep

#### JSON
```url
viacep.com.br/ws/CEP/json/
```

#### XML
```url
viacep.com.br/ws/CEP/xml/
```

---

### República Virtual

#### JSON
```url
http://cep.republicavirtual.com.br/web_cep.php?cep=CEP&formato=json
```

#### JavaScript
```url
http://cep.republicavirtual.com.br/web_cep.php?cep=CEP&formato=javascript
```

---

## 🖥️ Aplicações Disponíveis

### JavaFX

[BuscarCepJavaFX](https://github.com/GivaldoMedeirosNeto/buscarcep/tree/master/BuscarCepJavaFX)

Interface visual moderna utilizando JavaFX.

---

### Console

[BuscarCepConsole](https://github.com/GivaldoMedeirosNeto/buscarcep/tree/master/BuscarCepConsole)

Versão leve para execução via terminal.

---

## 📂 Estrutura do Projeto

```bash
BuscarCEP/
│
├── BuscarCepJavaFX/
├── BuscarCepConsole/
└── README.md
```
---

## 👨‍💻 Desenvolvido por Givaldo.