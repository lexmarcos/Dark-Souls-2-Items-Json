# Json de ~~_quase_~~ todos os itens do dark souls 2

O script pega as informações da wiki do jogo na qual cada página é referente a um tipo de item.
Ou seja se você precisar de todos as adágas do jogo, você informa o link da página onde está
as adágas na wiki e então o script irá selecionar todos eles e converter em um json

# Exemplo do json:

  ```
  {
        "Daggers": [
            "dagger",
            "royal dirk",
            "black flamestone dagger",
            "parrying dagger",
            "Bandits Knife",
            "Mythas Bent Blade",
            "Shadow Dagger",
            "Thief Dagger",
            "Broken Thief Sword",
            "Manikin Knife",
            "umbral dagger",
            "blue dagger",
            "Retainers Short Sword"
        ]
    }
  
  ```
  
  # Editando o script:
  Para editar o script basta modificar esse código abaixo, é nesse array que você informa quais item você quer buscar,
  entretando você deve antes se certificar que esse texto que será inserido no array faz parte do link na wiki, por exemplo:
  O link para pegar as ultra greatswords é: **https://darksouls2.wiki.fextralife.com/Ultra+Greatswords**.
  ou seja para pegar as ultra greatsword eu deveria colocar no array **"Ultra Greatswords"** sem o **+**, pois o script que decide
  onde vai colocar o **+**
  ```
 items = ["Ultra Greatswords", "Rings", "Greatswords",
         "Daggers", "Straight Swords", "Curved Swords",
         "Katanas", "Curved Greatswords", "Piercing Swords",
         "Axes", "Great Axes", "Hammers", "Great Hammers",
         "Fist Weapons", "Spears", "Halberds", "Lances",
         "Reapers", "Twinblades", "Whips", "Bows", "Greatbows",
         "Crossbows", "Flames", "Chimes", "Staves"]
  ```
  
  # Posso usar?
  Você pode usar, mas com a condição de dar créditos ao meu git 😊✌
  
  # Demo
  
  No momento o json está sendo usando no meu aplicativo [Souls Build](https://github.com/lexmarcos/soulsbuild)
  
  
