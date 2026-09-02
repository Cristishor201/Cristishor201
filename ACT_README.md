# Cum să rulezi act local

1. Generează un PAT (clasic) de la: https://github.com/settings/tokens
2. Permisiuni necesare: repo (pentru repository-uri private)
3. Creează `.actrc` cu:

```
echo "-s PAT_TOKEN=ghp_xxxxxxx" > .actrc
```

4. Adauga la `.gitignore`

```
.actrc   # act workflow local - testing
```

# Adaugat token si in setari repo

in repo settings/ secrets and variables/ actions -> Repository secrets -> adaugat `PAT TOKEN` si valoarea acestuia.