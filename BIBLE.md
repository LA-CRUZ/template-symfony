# Bible.md : 

## Scss conventions :

Filename : 
    - main.scss for the base file
    - _xxxxx.scss for imported files
    - /responsive/_xxxxxx.scss for responsive files

Media Queries : 
    - @media (max-width: 1400px) {}
    - @media (max-width: 991px) {}
    - @media (max-width: 770px) {}
    - @media (max-width: 450px) {}

Variables : 
    - color : $color-*project-name*-white
    - size : $size-*element*-height

Other :
    - All size in `rem` or `%`
    - prefer using class selector (.class) instead of id selector (#id)

## Css conventions :

Filename :
    - main.css for the base file
    - _xxxxx.css for imported files
    - /responsive/_xxxxx.css

Class :
    - kebab-case for class name

## Php conventions :

[Symfony standart](https://symfony.com/doc/current/contributing/code/standards.html)

Filename :
    - PascalCase for Class
    - UPPERCASE for constant class

Variables :
    - camelCase for methods and variables
    - snake_case for Twig variables

## Js conventions

Filename :
    - camelCase for files name

Variables :
    - camelCase for variables, and first caracter must be a letter
    - UPPERCASE for globals and constant
