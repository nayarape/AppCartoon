# Cartoon App 🎨

Um aplicativo React Native para buscar e gerenciar desenhos animados favoritos.

## 📱 Funcionalidades

- **Busca de Desenhos**: Pesquise desenhos animados por título usando a API OMDB
- **Detalhes do Desenho**: Visualize informações detalhadas incluindo sinopse, ano e gênero
- **Favoritos**: Adicione e remova desenhos da sua lista de favoritos
- **Armazenamento Local**: Os favoritos são salvos localmente no dispositivo

## 🛠️ Tecnologias Utilizadas

- **React Native**: Framework para desenvolvimento mobile
- **React Native Paper**: Biblioteca de componentes Material Design
- **React Navigation**: Navegação entre telas
- **Axios**: Cliente HTTP para requisições à API
- **AsyncStorage**: Armazenamento local de dados
- **OMDB API**: API para obter dados de desenhos animados e séries



## ⚙️ Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/cartoon-app.git
cd cartoon-app
```

2. Instale as dependências:
```bash
npm install
# ou
yarn install
```

3. Para Android:
```bash
npx react-native run-android
```

4. Para iOS:
```bash
npx react-native run-ios
```

## 📦 Dependências Principais

```json
{
  "react-native": "^0.x.x",
  "react-native-paper": "^x.x.x",
  "@react-navigation/native": "^x.x.x",
  "@react-navigation/stack": "^x.x.x",
  "axios": "^x.x.x",
  "@react-native-async-storage/async-storage": "^x.x.x"
}
```


## 📱 Telas do Aplicativo

### 🏠 Tela Inicial (HomeScreen)
- Campo de busca para inserir o nome do desenho animado
- Lista de resultados da busca
- Botão para navegar aos detalhes de cada desenho

### 🔍 Tela de Detalhes (DetailsScreen)
- Poster do desenho
- Título, sinopse, ano e gênero
- Botão para adicionar aos favoritos

### ⭐ Tela de Favoritos (FavoritesScreen)
- Lista de desenhos salvos como favoritos
- Opções para ver detalhes ou remover dos favoritos
- Otimizada para performance com FlatList

## 🚀 Funcionalidades Implementadas

- ✅ Busca de desenhos animados por título
- ✅ Exibição de detalhes completos
- ✅ Sistema de favoritos com persistência local
- ✅ Navegação fluida entre telas
- ✅ Interface responsiva com Material Design
- ✅ Otimizações de performance na lista de favoritos

## 🎨 Interface

O aplicativo utiliza React Native Paper para uma interface consistente e moderna, seguindo as diretrizes do Material Design.


## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

