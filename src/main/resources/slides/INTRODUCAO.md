---
title: Java Funcional - Boas Praticas
author: Diogo Fávero Fabrile.
patat:
    wrap: true
    margins:
        left: 10
        right: 10
...

~~~~~~~
     _                 ___             _               _         ___                  _         _     
  _ | |__ ___ ____ _  | __|  _ _ _  __(_)___ _ _  __ _| |  ___  | _ ) ___ _ __   __ _(_)_ _  __| |___ 
 | || / _` \ V / _` | | _| || | ' \/ _| / _ \ ' \/ _` | | |___| | _ \/ -_) '  \  \ V / | ' \/ _` / _ \
  \__/\__,_|\_/\__,_| |_| \_,_|_||_\__|_\___/_||_\__,_|_|       |___/\___|_|_|_|  \_/|_|_||_\__,_\___/
                                                                                                      
~~~~~~~

~~~~~~~


                   
   .----.          
  / .--. \         
 ' |    | '        
 \  '--'  /        
  `.    .'  ___    
  /  .-.  \|  /    
 /  /   \  \ /     
|  |     \  '.     
.'  \    /    `._  
 \   `--'  .`.   / 
  '._____.'   ` /  
                   


~~~~~~~

~~~~~~~


   ___                            _       
  / __\___  _ __   __ _ _ __ __ _| |_ ___ 
 / /  / _ \| '_ \ / _` | '__/ _` | __/ __|
/ /__| (_) | | | | (_| | | | (_| | |_\__ \
\____/\___/|_| |_|\__, |_|  \__,_|\__|___/
                  |___/                   


~~~~~~~

---

#Apresentação Pessoal

_Diogo Favero Fabrile_

* Experiência profissional 
    + 10 Anos de Experiência
        + Pequenas Empresas
        + Grandes Empresas
        + Experiência no exterior (Belgica & Alemanha)
        
* Certificações
    + OCJP 6 (Oracle Certified Java Programmer)
    + OCEJWCD 6(Oracle Certified Web Component Developer Certified Expert)
    + OCEEJBD 6(Oracle Certified Enterprise JavaBeans Developer Expert)
    + OCEJPAD 6(Oracle Certified Java Persistence API Developer)
    + OCEJWSD 6(Oracle Certified Java Web Service Developer)
    + IBM Cloud V1
        

---

# Objetivo do Curso (Alinhando expectativas)

##O que este curso não é?

* Não é um curso para aprender os conceitos basicos de streams, lambda e programação funcional

##O que esperar deste curso?

* Demonstrar boas praticas na utilização do paradigma funcional através de exemplos e comparações . 

    
---

# Apresentação do curso

* 01-Introdução do curso
    + [] _Objetivo do curso e pré-requisitos_
* 02-Mude sua forma de pensar.
    + [] _Imperativo vs Declarativo_
    + [] _Vantagens de se programar orientado a funções._
    + [] _POO acabou?_
* 03-Teoria na pratica (comparando Imperativo e Declarativo)
    + [] _Nosso Dominio_
    + [] _Exemplo basico de Imperativo vs Declarativo (Interação simplificada)_
    + [] _Mapeando nosso objeto (Imutabilidade)_
    + [] _Reutilizando nossas funções_
    + [] _Localizando elementos em nossas coleções(Entendendo Lazy Evaluation)_
    + [] _Escopo lexico(estatico) e como utilizar_
    + [] _Reduzindo nossas coleções Map Reduce (Contanto uma historia)_ 
* 04-Evolução das API's
    + [] _Files, Novas formas de utilizar_
    + [] _Collectors, como coletar nossos objetos_
    + [] _Comparators, como comparar seus objetos_
* 05-Criando suas API's utilizando lambda
    + [] _Por que temos os metodos default?_
    + [] _Codigo conciso_
    + [] _Strategy pattern vs Lambdas_
    + [] _Interfaces fluidas_
    + [] _O que fazemos com as exceptions?_
    + [] _Lidando com Resources_
    + [] _Compondo suas funções_
* 06-Seja Preguiçoso
    + [] _Procrastine até a ultima hora_
    + [] _Stream são preguiçosas, como elas se comportam?_
    + [] _Streams infinitas_
* 07-Paralelização de algoritimos
    + [] _Como utilizar a paralelização_
    + [] _Cuidados com a pralelização_
+ 08-Dicas Finais
    + [] _Lambdas e Method reference qual utilizar e porque?_
    + [] _Prefira as funções que ja estao presentes no java_
    + [] _Tente não retornar Streams diretamente em seu metodo_
    + [] _Classes anonimas são inuteis agora?_
    
    
---

---

~~~~~

             ________________________________________________
            /                                                \
           |    _________________________________________     |
           |   |                                         |    |
           |   |  C:\> See You soon!!                    |    |
           |   |                                         |    |
           |   |                                         |    |
           |   |                                         |    |
           |   |                                         |    |
           |   |                                         |    |
           |   |                                         |    |
           |   |                                         |    |
           |   |                                         |    |
           |   |                                         |    |
           |   |                                         |    |
           |   |                                         |    |
           |   |_________________________________________|    |
           |                                                  |
            \_________________________________________________/
                   \___________________________________/
                ___________________________________________
             _-'    .-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.  --- `-_
          _-'.-.-. .---.-.-.-.-.-.-.-.-.-.-.-.-.-.-.--.  .-.-.`-_
       _-'.-.-.-. .---.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-`__`. .-.-.-.`-_
    _-'.-.-.-.-. .-----.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-----. .-.-.-.-.`-_
 _-'.-.-.-.-.-. .---.-. .-------------------------. .-.---. .---.-.-.-.`-_
:-------------------------------------------------------------------------:
`---._.-------------------------------------------------------------._.---'
                              


~~~~~

---