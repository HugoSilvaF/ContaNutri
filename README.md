# ContaNutri
Sua alimentação na ponta dos dedos

**ContaNutri** é uma ferramenta prática e simples para calcular as calorias e os nutrientes dos alimentos, utilizando a API segura da **USDA FoodData Central**. O diferencial do projeto é que você pode calcular os nutrientes por grama apenas digitando o que comeu no chat, facilitando o controle alimentar no seu dia a dia.

## 🚀 Funcionalidades

- **Cálculo automático de nutrientes por grama**: Digite a descrição de um alimento (como "2 ovos", "100g de frango") e o sistema calcula as calorias, proteínas, carboidratos, gorduras, e outros nutrientes com base na quantidade informada.
- **Integração com a API da USDA FoodData Central**: Utiliza dados nutricionais atualizados de uma das maiores fontes confiáveis de dados alimentares.
- **Fácil de usar**: Tudo que você precisa fazer é digitar o nome do alimento e a quantidade, e o sistema fará todo o cálculo automaticamente.
- **Interface de chat interativa**: Receba os cálculos em tempo real com uma interface amigável e prática.

## 🛠️ Como Funciona

O **ContaNutri** funciona utilizando a API da **USDA FoodData Central**, que oferece uma base de dados extensa e confiável sobre os alimentos. Através desta integração, o sistema acessa os detalhes nutricionais de qualquer alimento informado, como calorias, proteínas, carboidratos, gorduras, vitaminas, minerais, entre outros.

### **Como calcular os nutrientes por grama?**

1. O usuário digita o alimento (ex.: "2 ovos", "100g de frango").
2. O sistema faz uma requisição à API da USDA, recupera os dados nutricionais do alimento.
3. Calcula os nutrientes **por grama** com base nas informações retornadas pela API.
4. Exibe as informações detalhadas dos nutrientes por grama diretamente no chat.

### **Exemplos de uso:**

- **Exemplo 1**:  
  Usuário digita:  
  `2 ovos`  
  O sistema retorna:  
  ```json
  {
    "Energy": "143 kcal",
    "Protein": "12.6 g",
    "Total Fat": "9.5 g",
    "Carbohydrates": "1.1 g"
  }
 - **Exemplo 2**:  
    Usuário digita:  
    `100g de frango desfiado`  
     O sistema retorna:  

    ```json
    {
      "Energy": "165 kcal",
      "Protein": "31 g",
      "Total Fat": "3.6 g",
      "Carbohydrates": "0 g"
    }
