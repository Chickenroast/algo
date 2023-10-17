code papier :

Leap year : si l'année peut étre divisée par 4 c'est une année bisextile.
Si elle peut etre divisée par 100 et également par 400 elle est bisextile
dans le cas contraire elle ne l'est pas

Leap year

Input :
const : enter a year (jour,mois,annee)
Read input

var boolean
if (year % 4 == 0)
OR if (year % 100 != 0) AND (year % 400 == 0)
return: true

var boolean
else == false
return: false
break

Right and left

1.  var string
    Input : enter a sentence(s) with a number(n)
    read : sentence,number

if s,n > null then {
position('s,n') check position on a string
return : 1 // return first letter
break
}
else s,n < null then {
return : enter a sentence with a number
}

2.  var string
    Input : enter a sentence(s) with a number(n)
    read : sentence,number
    if s,n > null then {
    position('s,n') check position on a string
    return : lenght('s,n') - position ,1 // return last letter
    break
    }
    else s,n < null then {
    return : enter a sentence with a number
    }

explain and translate

une fonction qui creer une liste de noms connecté à (n)
creer un tableau avec la liste de noms
creer une boucle qui commence avec un résultat a 0 tant que (n) n'aura pas été rempli
rentrer ton prenom qui sera inscrit dans "name"
rajoute le prenom entré a "name" et lui creer un emplacement dans
la liste des noms ou il sera stocké
ensuite il retourne la valeur de la liste des noms ou il y aura tout les name stocké

oh dis... j'ai demandé a chat de m'aider la pour le cout trop envie de faire du javascript note a moi meme check aprés ces langages

Go :

package main

import "fmt"

func createNameList(n int) []string {
listNames := make([]string, 0)
for i := 0; i < n; i++ {
var name string
fmt.Print("Enter your firstname: ")
fmt.Scanln(&name)
listNames = append(listNames, name)
}
return listNames
}

func main() {
n := 3 // Change the value of n as needed
names := createNameList(n)
fmt.Println(names)
}

Pascal

program CreateNameList;
var
ListNames: array of string;
i, n: integer;
name: string;
begin
write('Enter the number of first names: ');
readln(n);
SetLength(ListNames, 0);
for i := 1 to n do
begin
write('Enter your firstname: ');
readln(name);
SetLength(ListNames, Length(ListNames) + 1);
ListNames[High(ListNames)] := name;
end;
writeln('List of names:');
for i := 0 to High(ListNames) do
writeln(ListNames[i]);
end.

Bash

#!/bin/bash

create_name_list() {
list_names=()
read -p "Enter the number of first names: " n
for ((i=0; i<n; i++)); do
read -p "Enter your firstname: " name
list_names+=("$name")
  done
  echo "List of names:"
  for name in "${list_names[@]}"; do
echo "$name"
done
}

create_name_list

multiplication table
