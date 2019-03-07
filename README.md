# Makefile
Makefile inicialmente concebido por [Leonardo Cesar Teonacio Bezerra](https://github.com/leobezerra).

## Explicando

Atende a seguinte organização de projeto:

- `bin`: arquivos binários;
- `src`: arquivos-fonte (.c/.cpp);
- `include`: arquivos .h;
- `application`: arquivo main do projeto;
- `build`: arquivos-objetos (.o);
- `test`: arquivos para testar a aplicação.

### Comandos

- `make`: compila o projeto;
- `make test`: compila e executa os testes;
- `make clean`: limpa os arquivos-objetos;
- `make init`: cria as pastas do projeto, atendendo a organização mostrada anteriormente.