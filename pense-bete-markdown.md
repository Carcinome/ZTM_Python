
# 📝 Pense-bête Markdown – Alfred Edition

Markdown est un langage de balisage léger qui permet de mettre en forme du texte **sans se prendre la tête**.  
Pratique pour les README, la doc ou tes notes !

---

## 1. **Titres**
| Résultat | Syntaxe |
|-----------|----------|
| `#` Titre 1 | `# Titre 1` |
| `##` Titre 2 | `## Titre 2` |
| `###` Titre 3 | `### Titre 3` |
| Jusqu'à `######` | `###### Titre 6` |

💡 *Astuce Batman* : Ne colle pas le `#` au texte, laisse un espace (`# Mon titre` ✅).

---

## 2. **Texte**
| Effet | Syntaxe |
|--------|----------|
| **Gras** | `**texte**` |
| *Italique* | `*texte*` |
| ***Gras + Italique*** | `***texte***` |
| ~~Barré~~ | `~~texte~~` |

---

## 3. **Listes**
### Puces
```markdown
- Élément 1
- Élément 2
  - Sous-élément
    - Sous-sous-élément
```
**Rendu :**
- Élément 1  
- Élément 2  
  - Sous-élément  
    - Sous-sous-élément  

---

### Numérotée
```markdown
1. Premier
2. Deuxième
3. Troisième
```
**Rendu :**
1. Premier  
2. Deuxième  
3. Troisième  

---

## 4. **Liens et Images**
| Type | Syntaxe | Exemple |
|------|----------|---------|
| Lien | `[texte](https://exemple.com)` | [OpenAI](https://openai.com) |
| Image | `![alt](image.png)` | ![Logo](https://www.markdownguide.org/assets/images/tux.png) |

---

## 5. **Code**
### Inline
Pour une petite portion de code :  
\``print("Hello")`` → `print("Hello")`

---

### Bloc de code
\```python  
print("Hello Batman")  
\```  

**Rendu :**
```python
print("Hello Batman")
```

💡 *Astuce Alfred* : précise le langage après les trois backticks pour la coloration syntaxique (`python`, `bash`, `json`, etc.).

---

## 6. **Citations**
```markdown
> Ceci est une citation.
>> Et ceci est une sous-citation.
```

**Rendu :**
> Ceci est une citation.  
>> Et ceci est une sous-citation.

---

## 7. **Tableaux**
```markdown
| Colonne 1 | Colonne 2 | Colonne 3 |
|-----------|-----------|-----------|
| Valeur 1  | Valeur 2  | Valeur 3  |
| A         | B         | C         |
```

**Rendu :**

| Colonne 1 | Colonne 2 | Colonne 3 |
|-----------|-----------|-----------|
| Valeur 1  | Valeur 2  | Valeur 3  |
| A         | B         | C         |

---

## 8. **Séparateurs**
Pour créer une ligne horizontale :

```
---
```

**Rendu :**

---

---

## 9. **Cases à cocher**
```markdown
- [ ] Tâche à faire
- [x] Tâche terminée
```

**Rendu :**
- [ ] Tâche à faire  
- [x] Tâche terminée  

---

## 10. **Combinaisons pratiques**
### Exemple README
```markdown
# Mon Projet

## Description
Petit projet pour apprendre Markdown.

## Installation
```bash
git clone https://github.com/user/projet.git
cd projet
```

## TODO
- [x] Faire la structure
- [ ] Ajouter des fonctionnalités
- [ ] Documenter le code
```
