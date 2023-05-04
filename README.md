# Git

## Configuração do usuário das alterações

Fonte: [Configuração do Git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git) 

```
 git config --global user.name "Ronald Studart"
```
```
git config --global user.email ronaldstudart@hotmail.com
```

## Subir alterações para o repositório remoto


### 1 -  Verificar as alterações
```
git status
```
### 2 -  Adicionar as alterações que serão enviadas

```
git add.
```
### 3 -  Conferir as alterações enviadas

```
git status
```
### 4 -  Preparar as alterações para serem enviadas

```
git commit -m "comentário"
```
### 5 -  Conferir a preparação 

```
git status
```
### 6 -  Envia as alterações
```
git push
```