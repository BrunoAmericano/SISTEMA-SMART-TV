# 📺 Smart TV - Simulação de um Sistema de TV Inteligente

Este é um pequeno projeto em Java que simula o funcionamento básico de uma Smart TV, permitindo ligar, desligar, mudar de canal e ajustar o volume. Ideal para quem está iniciando na programação orientada a objetos! 🚀

---

## 🚀 Funcionalidades Implementadas

✅ Ligar e desligar a TV  
✅ Alterar canal manualmente  
✅ Aumentar e diminuir o canal  
✅ Aumentar e diminuir o volume  

---

## 🛠️ Estrutura do Projeto

O projeto é composto por duas classes principais:

### 1️⃣ **SmartTv.java**
Esta classe representa a Smart TV e possui os seguintes atributos:
- **`ligada`** (boolean) - Indica se a TV está ligada ou desligada.
- **`canal`** (int) - Armazena o canal atual da TV.
- **`volume`** (int) - Controla o volume da TV.

#### 📌 Métodos da classe `SmartTv`:
- `ligar()` - Liga a TV.
- `desligar()` - Desliga a TV.
- `mudarCanal(int novoCanal)` - Altera o canal para um valor específico.
- `aumentarCanal()` - Incrementa o canal.
- `diminuirCanal()` - Decrementa o canal.
- `aumentarVolume()` - Aumenta o volume e exibe a nova configuração.
- `diminuirVolume()` - Diminui o volume e exibe a nova configuração.

### 2️⃣ **Usuario.java**
Classe que testa o funcionamento da `SmartTv`, criando um objeto e interagindo com seus métodos.

---

## 🏗️ Como Executar o Projeto

1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Navegue até a pasta do projeto:
   ```sh
   cd nome-do-projeto
   ```
3. Compile os arquivos Java:
   ```sh
   javac SmartTv.java Usuario.java
   ```
4. Execute o programa:
   ```sh
   java Usuario
   ```

---

## 🎯 Exemplo de Saída Esperada

```sh
Diminuindo o volume para: 24
Diminuindo o volume para: 23
Diminuindo o volume para: 22
Aumentando o volume para: 23
Canal Atual : 1
Canal Atual : 13
Volume Atual : 23
TV Ligada ?false
Canal Atual : 13
Volume Atual : 23
Novo Status -> TV Ligada ?true
Novo Status -> TV Ligada ?false
``` 

---

## 📝 Contribuição
Fique à vontade para sugerir melhorias ou modificar o código. Pull requests são bem-vindos! 🚀

