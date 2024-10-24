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


#✨ Notes de base sur JavaScript 🌟
## 📌 1. Mot-clé `var`
- **`var`** : Utilisé pour déclarer une variable.
  - **Exemple** :
    ```javascript
    var a = 3;
    ```

---

## 📌 2. Fonction `Math.round()` pour arrondir
- **`Math.round()`** : Fonction intégrée en JavaScript qui **arrondit le nombre** à l'entier le plus proche.
  - **Exemple** :
    ```javascript
    console.log(Math.round(4.7));  // Affiche : 5
    ```

---

## 📌 3. Boucle `for`
- **Boucle `for`** : Permet d'exécuter un bloc de code plusieurs fois, selon une condition.
  - **Syntaxe** :
    ```javascript
    for (début; condition d'arrêt; étape) {
        // Code à exécuter à chaque itération
    }
    ```
  - **Exemple** : Supposons qu'il y ait 5 pommes. On commence à les compter à partir de 0 jusqu'à 4, et on imprime un message à chaque fois qu'on en mange une.
    ```javascript
    for (let i = 0; i < 5; i++) {
        console.log("J'ai mangé la " + i + "ème pomme");
    }
    ```

---

## 📌 4. Nombre aléatoire avec `Math.random()`
- **`Math.random()`** : Génère un **nombre aléatoire** entre 0 et 1.
  - **Exemple** :
    ```javascript
    let randomNum = Math.random();
    console.log(randomNum);
    ```

---

## 📌 5. Concatenation de chaîne `+=`
- **`Str += arr[num]`** : Signifie que **`arr[num]` est ajouté à la fin de `Str`**, permettant ainsi de concaténer les chaînes.
  - **Exemple** :
    ```javascript
    let str = "";
    let arr = ['a', 'b', 'c'];
    let num = 1;
    str += arr[num];  // str devient 'b'
    ```

---

## 📌 6. Propriété `element.value`
- **`element.value`** : Permet d'obtenir ou de définir la valeur d'un élément HTML.
  - **Exemple** :
    ```javascript
    let inputValue = document.getElementById("monInput").value;
    ```

---

## 📌 7. Opérateur de différence `!=`
- **`!=`** : Compare si deux valeurs sont différentes. Si elles sont différentes, retourne `true`; sinon, retourne `false`.
  - **Exemple** :
    ```javascript
    if (a != b) {
        console.log("a et b sont différents");
    }
    ```



# ✨ JavaScript 笔记 🌟

## 📌 1. `var` 关键字
- **`var`**：用于声明一个变量。
  - **例子**：
    ```javascript
    var a = 3;
    ```

---

## 📌 2. `Math.round()` 四舍五入函数
- **`Math.round()`**：JavaScript 中的内置函数，**用于四舍五入**括号中的数字。
  - **例子**：
    ```javascript
    console.log(Math.round(4.7));  // 输出：5
    ```

---

## 📌 3. `for` 循环
- **`for` 循环**：用于按特定次数循环执行代码。
  - **语法**：
    ```javascript
    for (开始; 什么时候停; 做什么) {
        // 每次循环要执行的代码
    }
    ```
  - **例子**：假设有 5 个苹果，从 0 开始数，一直到 4 停，每数一个就打印你吃了第几个苹果。
    ```javascript
    for (let i = 0; i < 5; i++) {
        console.log("我吃了第" + i + "个苹果");
    }
    ```

---

## 📌 4. `Math.random()` 随机数
- **`Math.random()`**：生成一个**0 到 1 之间**的随机小数。
  - **例子**：
    ```javascript
    let randomNum = Math.random();
    console.log(randomNum);
    ```

---

## 📌 5. 字符串拼接 `+=`
- **`Str += arr[num]`**：表示**将 `arr[num]` 加到 `Str` 后面**，相当于拼接字符串。
  - **例子**：
    ```javascript
    let str = "";
    let arr = ['a', 'b', 'c'];
    let num = 1;
    str += arr[num];  // str 现在是 'b'
    ```

---

## 📌 6. `element.value`
- **`element.value`**：可以获取或设置某个 HTML 元素的内容。
  - **例子**：
    ```javascript
    let inputValue = document.getElementById("myInput").value;
    ```

---

## 📌 7. 不等于操作符 `!=`
- **`!=`**：比较两个值是否不相等，如果不相等返回 `true`，相等返回 `false`。
  - **例子**：
    ```javascript
    if (a != b) {
        console.log("a 和 b 不相等");
    }
    ```

}




