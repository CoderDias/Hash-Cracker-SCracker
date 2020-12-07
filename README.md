# SolyCrack
Quebrar hash com wordlist automatica.

@Author : Soly

@Version : 1.1

@SecurityBreaker

{GitHub : https://github.com/CoderDias/ }


## Uso do script
[!] Uso : scrack.py <hash> <min_length> <max_length> --chars=<characters> OU --wordlist=<wordlist_template> --type=<md5|sha1|sha512>

[-] Argumentos
 1. hash => hash que deseja quebrar
 2. min_length => tamanho minimo para tentar
 3. max_length => tamanho maximo para tentar
 4. --chars => testa somente com os caracters passados
 5. --wordlist => testa com o template de wordlist escolhido
 6. --type => tipo da hash
 
 
[-] Wordlists com strings
 1. wd_all => todas as senhas possiveis
 2. wd_chars => todas as senhas com letras possiveis
 3. wd_chars_min => todas as senhas com letras minusculas possiveis
 4. wd_chars_upper => todas as senhas com letras maiusculas possiveis


[-] Wordlists numericas e especiais
 1. wd_num => todas as senhas numericas possiveis
 2. wd_special => todas as senhas com caracteres especiais possiveis


[-] Wordlists combinadas
 1. wd_chars_min_num => todas as senhas com letras minusculas e numeros possiveis
 2. wd_chars_upper_num => todas as senhas com letras maiusculas e numeros possiveis
