# 📱 AdMob React Native App

<p align="center">
  <img src="https://img.shields.io/badge/React%20Native-0.60.5-blue" alt="React Native"/>
  <img src="https://img.shields.io/badge/AdMob-2.0.0--beta.5-yellow" alt="AdMob"/>
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License"/>
  <img src="https://img.shields.io/badge/status-Em%20Desenvolvimento-orange" alt="Status"/>
</p>

---

<p align="center">
  <b>Aplicativo de exemplo utilizando <span style="color:#1976d2">React Native</span> e integração com <span style="color:#e53935">Google AdMob</span> para banners de anúncios.</b>
</p>

---

## 📑 Sumário
- [🚀 Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [🏛️ Padrões de Projeto](#️-padrões-de-projeto)
- [⚙️ Configuração e Setup](#️-configuração-e-setup)
- [📢 Configuração do AdMob](#-configuração-do-admob)
- [📜 Scripts Disponíveis](#-scripts-disponíveis)
- [📁 Estrutura do Projeto](#-estrutura-do-projeto)
- [👤 Autor](#-autor)

---

## 🚀 Tecnologias Utilizadas
- **[React Native 0.60.5](https://reactnative.dev/)**
- **[React 16.8.6](https://reactjs.org/)**
- **[react-native-admob 2.0.0-beta.5](https://github.com/sbugert/react-native-admob)**
- **[Jest](https://jestjs.io/)** _(testes)_
- **[ESLint](https://eslint.org/)** _(lint)_
- **[Babel](https://babeljs.io/)** _(transpiler)_

---

## 🏛️ Padrões de Projeto
- 🧩 **Componentização funcional**: Uso de componentes funcionais e hooks do React.
- 🗂️ **Separação de responsabilidades**: UI, lógica de anúncios e estilos organizados.
- ⚡ **Configuração padrão do React Native** (sem customizações avançadas).

---

## ⚙️ Configuração e Setup

> **Pré-requisitos:**
> - Node.js >= 10
> - Yarn >= 1.17
> - Android Studio/Xcode configurados para build mobile

1. **Instale as dependências:**
   ```bash
   yarn install
   ```
2. **Execute o projeto:**
   - Android:
     ```bash
     npx react-native run-android
     ```
   - iOS:
     ```bash
     npx react-native run-ios
     ```
3. **Inicie o Metro Bundler:**
   ```bash
   yarn start
   ```

---

## 📢 Configuração do AdMob
- O projeto utiliza o pacote `react-native-admob` para exibir banners.
- Altere o `adUnitID` no componente `<AdMobBanner />` em `App.js` para o ID real do seu app/admob.
- Para testes, utilize o ID de teste fornecido pela AdMob.

---

## 📜 Scripts Disponíveis
- `yarn start` — Inicia o Metro Bundler
- `yarn test` — Executa os testes com Jest
- `yarn lint` — Executa o linter (ESLint)

---

## 📁 Estrutura do Projeto
```
├── App.js              # Componente principal do app
├── index.js            # Entry point do React Native
├── package.json        # Dependências e scripts
├── android/            # Projeto Android
├── ios/                # Projeto iOS
├── __tests__/          # Testes automatizados
```

---

## 👤 Autor
by **Rodolfo M. F. Abreu**


---

<p align="center">
  <i>Projeto de exemplo para integração do Google AdMob em React Native 0.60.x</i><br/>
</p>
