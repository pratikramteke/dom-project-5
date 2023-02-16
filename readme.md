# Project 5

## Original Output Image

![Original Ouptput Image](./original%20output%20image.png)

## Task 1: Achieve the following Output using JavaScript DOM Manipulation

![Task 1 Image](./Output/DOM%20P2%20SS.png)

## JavaScript Code:

```js
const nav = document.querySelector(".nav-center");
const a = document.createElement("a");
const recipes = document.querySelector(".tags-container");
const chinese = document.createElement("a");
const recipeGallery = document.querySelector(".recipe-gallery");
const card = document.createElement("div");

a.href = "#";
a.className = "btn";
a.innerText = "Pro Subscription";
nav.children[2].append(a);

chinese.href = "#";
chinese.innerText = "Chinese (7)";
recipes.children[1].append(chinese);

card.className = "card";
card.innerText = "add 6th card here";
recipeGallery.append(card);
```
