# Page de Vérification - Générateur de Code de Vérification

Ce projet est une simple page web permettant de générer un code de vérification aléatoire et de le comparer avec l'entrée utilisateur. Le code de vérification est composé de caractères alphanumériques (0-9 et a-f) et permet à l'utilisateur de valider un formulaire avec le bon code.


## Capture d'écran principale

![Capture principale](./images%20de%20la%20fin/principal.png)

## Exemple de code incorrect

![Code incorrect](./images%20de%20la%20fin/incorrect.png)

## Exemple de succès

![Succès](./images%20de%20la%20fin/succes.png)



## Fonctionnalités

- Génération de codes de vérification aléatoires (6 caractères).
- Possibilité de générer un nouveau code si celui affiché est illisible.
- Validation de l'entrée utilisateur contre le code généré.
- Affichage d'un message d'alerte si le code est incorrect.

## Technologies Utilisées

- **HTML5** : Structure de la page.
- **CSS3** : Stylisation de la page.
- **JavaScript** : Logique de génération et de validation des codes.

## Installation et Utilisation

1. **Cloner le dépôt** :
    ```bash
    git clone https://github.com/votre-utilisateur/nom-du-projet.git
    ```

2. **Accéder au dossier du projet** :
    ```bash
    cd nom-du-projet
    ```

3. **Ouvrir le fichier `index.html`** dans un navigateur pour tester l'application localement.

## Fonctionnement

- Au chargement de la page, un code de vérification aléatoire est généré et affiché.
- L'utilisateur peut entrer ce code dans le champ prévu à cet effet.
- En cliquant sur le bouton **"Valider"**, le code saisi est comparé au code affiché. Si les deux correspondent, un message de confirmation s'affiche. Sinon, un message d'erreur apparaît et le champ d'entrée est réinitialisé.
- Si le code est difficile à lire, l'utilisateur peut cliquer sur **"Changer si illisible"** pour générer un nouveau code.

## Structure du Projet

```bash
nom-du-projet/
│
├── index.html         # Fichier HTML principal
└── README.md          # Ce fichier de documentation


- 🌟 **var**: 用于声明一个变量，例如 `var a = 3`

- 🌟 **Math.round( )**: JS中的一个内置函数，把 `()` 里面的数四舍五入  
  💡 例子：`console.log(Math.round(4.7));` 输出 5

- 🌟 **for 循环**: 语法：`for (开始; 什么时候停; 怎么做法)`  
  🍏 例子：假设有 5 份苹果，想从 0 开始数，一直到 4 停，数字是一个数，每数一次就说你吃了第几个苹果。  
  ```javascript
  for (let i = 0; i < 5; i++) {
      console.log("我吃了第 " + i + " 个苹果");
  }
📌 这里 `+ i +` 是将文本和变量 "i" 拼接起来的方式。

- 🌟 **Math.random( )**: 这是一个用来生成 0 - 1 的小数随机函数。🎲

- 🌟 **Str += arr[num]**: 意思是把 `arr[num]` 加到 `Str` 后面。🧩

- 🌟 **element.value**: 可以获取 `element` 的内容  
  例如：`value = "..."` 📥

- 🌟 **!=**: 比较两个值是否相等。若不相等则返回 `True`，相等则返回 `False`。✅❌



