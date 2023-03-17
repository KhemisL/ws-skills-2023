# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE  ✔️
l'intéret de TypeScript est de typé fortement notre code ( function, variable state context... ) pour éviter les erreurs de type
- les types de bases  ✔️
TypeScript comprend plusieur type , comme any, les type primitifs ( string, number, boolean...) et les types pérsonnalisé comme les interfaces
```javascript
let ma_variable: any = valeur; 

// type primitif
let nom_variable: string = valeur; 
let nom_variable: number = valeur; 
let nom_variable: bolean = valeur; 
let nom_variable: void = valeur; 
let nom_variable: null = valeur; 
let nom_variable: undefined = valeur; 

// les interface et type pérsonalisé
interface my_interface { 
   name:string, 
   my_function: ()=>string 
}

type my_type = { 
   name:string, 
   my_function: ()=>string 
} 
- comment et pourquoi étendre une interface ❌ / ✔️
- les classes et les decorators ❌ / ✔️

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️
```javascript
///////interface ///////
interface IUser {
  name: string;
  age?: number;
  birthday?: string;
}
/////// finish ///////

/////// function ///////
const prettyPrintWilder = (users: IUser[]): void => {
  users.map((user) => {
    console.log(`${user.name} is ${user.age} years old`);
  });
};
/////// finish ///////

/////// test ///////
const wilders: IUser[] = [];
const user1 = { name: "Pierre", age: 23 };
const user2 = { name: "Paul", birthday: "10/02/1990" };
const user3 = { name: "Jacques", age: 25 };
wilders.push(user1);
wilders.push(user2);
wilders.push(user3);
prettyPrintWilder(wilders);
/////// finish ///////
```

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
