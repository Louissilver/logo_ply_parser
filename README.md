# Lexer + Parser + Python Ply (Python Lex-Yacc)

<img src="https://images.squarespace-cdn.com/content/v1/5f23770e451c1e2a6109896d/c0220830-24da-4967-b21d-573278db4a87/Python+Logo+Webpng.png?format=500w" alt="Python PLY">

### Universidade La Salle - Curso de Ciência da Computação

## Ferramentas utilizadas:

- Python versão 3.10.2

## Setup do projeto

### Clonando o projeto

1. Clique no botão 'Clone'
2. Escolha uma das opções (_Clone with SSH_ ou _Clone with HTTPS_) e então clique no botão _Copy URL_ ao lado do campo da opção escolhida
3. No terminal, no diretório onde você armazena seus projetos de software, digite `git clone [URL copiada no passo anterior] e pressione ENTER

     - Exemplo: 
```
git clone https://github.com/Louissilver/logo_ply_parser
```
4. Por fim, acesso o diretório do projeto recém clonado (`cd logo_ply_parser`)

### Instalando as bibliotecas

Para rodar o programa é necessário instalar a biblioteca Ply. Para isso utilize o comando abaixo:

```pip3 install ply```

### Inicializando o programa

No terminal, dentro do diretório `logo_ply_parser/`, execute o comando `python .\logo.py` para executar o programa

Para testar, cole o comando abaixo no console:

```
to square :a, :b
forward :a
left:b
forward :a 
left:b
forward :a
left:b
forward :a
left:b 
end
```
Após isso, pressione 'Enter' duas vezes para gerar a árvore sintática

## 🚀 Criado por

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/113436486?v=4" width="100px;" alt="Foto do Leonardo Auler no GitHub"/><br>
        <sub>
          <b>Leonardo Auler</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/63754409?v=4" width="100px;" alt="Foto do Luís da Silveira no GitHub"/><br>
        <sub>
          <b>Luís Fernando da Silveira</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## Referências

Para construir o código, foram utilizadas como base as aulas do professor da disciplina de compiladores: [Rafael Jeffmann](https://github.com/rafasgj)

Além disso, foi utilizado como suporte o código [LogoPy](https://github.com/mwojtulewicz/LogoPy/tree/065cd063da57d8f28422db7da6517bed51553c96)