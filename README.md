# CSS Fundamentos

## ✔Position
### 1️⃣ Relative
`position: relative;`

Quando utilizada ela, no começo aparentemente não acontece nada, porém "Ativamos" 4 propriedades: 
`top`
`right`
`left`
`bottom` 

###  2️⃣  Absolute
`position: absolute;`

Ele sai do fluxo normal do documento HTML, e acaba ficando com seu próprio fluxo de posicionamento na página. 

![image](https://user-images.githubusercontent.com/69365572/145476666-004cb11a-a659-4340-a6ae-6ae6456b6816.png)


Mas se eu quiser que ele fique com a propriedade absoluto, mas relativo à algum elemento, eu preciso utilizar no elemento `position: relative`.

```
.box{
    width: 400px;
    height: 400px;
    border: 5px solid black;
    position: relative;
}
```
```
.item1{
    background-color: red;
    position: absolute;
    bottom: 0;
}
```
![image](https://user-images.githubusercontent.com/69365572/145476591-8a0e3ead-88f0-4590-af7d-b50d83aff074.png)


### 3️⃣ Fixed
`position: fixed;`

Ele vai deixar o nosso conteúdo fixo na página, então quando a gente descer a página, o conteúdo vai estar ali fixo. Como na propriedade relative, podemos usar os 4 elementos
`top`
`right`
`left`
`bottom` 
