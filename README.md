# File Encryptor

Este é um programa simples em C# para criptografar e descriptografar arquivos usando o algoritmo AES (Advanced Encryption Standard). Além disso, ele inclui a funcionalidade de adicionar o arquivo descriptografado à lista de exclusões do Windows Defender e executá-lo como administrador.

## Funcionalidades

1. **Criptografia de Arquivos:** Você pode criptografar arquivos usando uma chave de criptografia AES e um vetor de inicialização (IV).
2. **Descriptografia de Arquivos:** Você pode descriptografar arquivos previamente criptografados usando a mesma chave e IV.
3. **Adicionar à Lista de Exclusões do Windows Defender:** O programa adiciona automaticamente o arquivo descriptografado à lista de exclusões do Windows Defender para evitar que seja escaneado.
4. **Executar como Administrador:** Após descriptografar o arquivo, ele é executado automaticamente como administrador.

## Pré-requisitos

- Este programa requer permissões de administrador para executar a funcionalidade de adicionar à lista de exclusões do Windows Defender e para executar o arquivo descriptografado.
