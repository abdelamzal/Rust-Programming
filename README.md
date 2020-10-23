# Rust-Programming

## Installation :
installer Rust :

installer C++ :

installer les dépendencesVSCode :

## 1 : Hello-world (Rust script) 
Créer un fichier main.rs

```
fn main() {
    println!("Hello, world!");
}
```

> PS C:\ rustc main.rs

> PS C:\ main.exe


## 2 : Hello-world (Rust cargo) 
> PS C:\ cargo new hello-world-cargo --bin

> PS C:\ cargo run


## 3 : Commentaire : 
> // commentaire sur une ligne 

>/*

>> Commentaire sur plusieurs lignes 

>*/ 

## 4 : Variables :

```
fn main() {
    let y = 30;
    let mut x = 45;

    println!("La valeur de y est {} ", y);
    println!("La valeur de x est {} ", x);

    x = 60;
    println!("La valeur de y ne peut pas être changée ");
    println!("La valeur de x est {} ", x);
}
```

let nom_variable = valeur;
> la variable ne peut pas etre changée

let mut nom_variable = valeur; 
> la valeur de la de variable peut etre changée 

## 5 : Data types :

Les types premitives en Rust : 
 - integer : i32 ou i64
 - unsigned integer : u32 ou u64
 - float
 - boolean
 - char 

## 6 : If Else :