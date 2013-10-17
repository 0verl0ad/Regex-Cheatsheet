Regex-Cheatsheet
================

Little cheatsheet with some perl regexp examples to use.

1. Sacar texto entre dos delimitadores (multilinea y todas las veces que aparezca)
 m/deli(.*?)mitador/gm

2. Pasar cadena hexadecimal a ASCII $buscar =~ s/([a-fA-F0-9][a-fA-F0-9])/chr(hex($1))/eg;
