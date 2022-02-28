# SCracker

> @Author : Soly <br>
> @Version : 1.1<br>
> @CoderDias<br>

```
Official GitHub : https://github.com/CoderDias/Hash-Cracker-SCracker
```

## Uso do script
```
scrack.py <hash_string> <min_length> <max_length> --chars=<custom_chars> OU --wordlist=<wordlist_template> --type=<md5|sha1|sha512>
```

### [-] Argumentos
> - hash => hash que deseja quebrar
> - min_length => tamanho minimo para tentar
> - max_length => tamanho maximo para tentar
> - --chars => testa somente com os caracters passados
> - --wordlist => testa com o template de wordlist escolhido
> - --type => tipo da hash
 
 
### [-] Wordlists com strings
> - wd_all => todas as senhas possiveis
> - wd_chars => todas as senhas com letras possiveis
> - wd_chars_min => todas as senhas com letras minusculas possiveis
> - wd_chars_upper => todas as senhas com letras maiusculas possiveis


### [-] Wordlists numericas e especiais
> - wd_num => todas as senhas numericas possiveis
> - wd_special => todas as senhas com caracteres especiais possiveis


### [-] Wordlists combinadas
> - wd_chars_min_num => todas as senhas com letras minusculas e numeros possiveis
> - wd_chars_upper_num => todas as senhas com letras maiusculas e numeros possiveis

### Requirementos

- Python **2.7.x**+

### Disclaimer

```
THE SCRIPT IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR

IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,

FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE

AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER

LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,

OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE

SOFTWARE. THIS SOFTWARE IS PURELY FOR EDUCATIONAL PURPOSES.
```
