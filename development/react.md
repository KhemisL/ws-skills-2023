# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant  ✔️
```javascript
const [state, setState] = useState(""); // state = valeur du state, setState = modification state
```
- les composants enfants et les _props_ qu'on leur passe  ✔️
```javascript
const exemple = ({ props }) => {
```
- le déclenchement d'instructions en fonction des actions de l'utilisateur  ✔️
```javascript
<button onClick={} onChange={}>...</button>
```
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props  ✔️
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant ❌
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext`  ✔️
```javascript
export const WildersContext = createContext();
```

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️
```javascript
import React, { useContext } from "react";
import axios from "axios";
import { WildersContext } from "../../contexts/WilderContext";

const DeleteWilder = ({ id }) => {
  const { fetchData } = useContext(WildersContext);
  /////////// logique //////////////
  const handleDelete = () => {
    axios.delete(`http://localhost:3001/api/wilder/users/delete/${id.id}`);
    fetchData();
  };
  /////////// finish //////////////

  return (
    <div className="delete-wilder" onClick={handleDelete}>
      X
    </div>
  );
};

export default DeleteWilder;
```

### Utilisation dans un projet ✔️

[lien github](https://github.com/WildCodeSchool/2023-03-wns-lamarr-groupe1)

Description :

### Utilisation en production si applicable❌

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌

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
