## Projeto de Fixação do Aprendizado

### Decifrando vários documentos de uma vez

Nosso objetivo com esse exercício é decifrar vários arquivos de texto que tenham sido criptografados com uma cifra de César.

A função [listdir(path='.')](https://docs.python.org/3.5/library/os.html?highlight=listdir#os.listdir) do módulo [os](https://docs.python.org/3.5/library/os.html?highlight=listdir#os.listdir) retorna uma lista com o nome de todos os arquivos e pastas dentro de uma determinada pasta. Vamos utilizar esta lista como base e filtrá-la usando *list comprehension* para obter apenas os arquivos desejados, isto é, apenas os arquivos que terminam com "\_cifrado.txt".

Crie um programa que recebe o caminho de um diretório (uma pasta) e decifra todos os documentos neste diretório que tenham sido cifrados usando o padrão que estamos estudando. Cuidado, Os demais arquivos devem se manter inalterados!

Dica:
  Você pode verificar se uma string termina com um dado sufixo usando a função "endswith(sufixo)". Se a string em questão termina com o sufixo dado, a função retorna True, caso contrário, ela retorna False:
```python
  nome_do_arquivo = "ferias.jpg"
  if nome_do_arquivo.endswith(".txt"):
      print("Esse é um arquivo de texto comum")
  elif nome_do_arquivo.endswith(".jpg"):
      print("Esse é um arquivo de imagem)
  else:
      print("Não reconheci esse tipo de arquivo, tente outro programa.")
```
