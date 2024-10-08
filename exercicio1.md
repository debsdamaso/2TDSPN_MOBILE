# Exercício 1: App de Lista de Compras Simples com AsyncStorage e Navegação

## Objetivo:
Criar um aplicativo React Native que permita aos usuários adicionar, visualizar e remover itens de uma lista de compras simples. Utilize `AsyncStorage` para armazenar os itens localmente e implemente navegação entre telas usando **React Navigation**.

## Passos:

1. **Setup do Projeto:**
   - Crie um novo projeto React Native.
   - Instale as dependências para `AsyncStorage` e `React Navigation` (Stack Navigator).

2. **Tela Principal (Lista de Compras):**
   - Utilize `useState` para criar um estado que armazene os itens da lista.
   - Exiba os itens atuais da lista em um `FlatList`.
   - Adicione um botão que navega para a tela de adicionar itens.

3. **Tela de Adicionar Itens:**
   - Crie uma segunda tela onde o usuário pode adicionar novos itens.
   - Ao adicionar, o item deve ser salvo no estado global (usando `AsyncStorage`) e, ao voltar para a tela principal, os itens devem ser atualizados.
   - Use `useEffect` para carregar os itens do `AsyncStorage` na inicialização do app.

4. **Remover Itens:**
   - Ao clicar em um item na tela principal, remova-o do estado e do `AsyncStorage`.

## Requisitos:
- Implementar **React Navigation** com duas telas: uma para a lista de compras e outra para adicionar itens.
- Armazenar os itens da lista utilizando `AsyncStorage`.
- Usar `useState` para gerenciar os itens em tempo real.
- Usar `useEffect` para carregar os dados do `AsyncStorage` na inicialização.

## Dicas:
- Para navegar entre as telas, utilize `navigation.navigate()` do React Navigation.
- Utilize `AsyncStorage.setItem` e `AsyncStorage.getItem` para manipular os dados.

---

