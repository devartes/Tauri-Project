# Tauri-Project


Este projeto é um teste meu do [Tauri](https://tauri.app/)

Para criar um projeto do zero, como esse:

Primeiro é necessário o Vite:</br>
`npm init vite@latest`

Escolha o tipo do projeto</br>
Exemplo:

√ Project name: ... meuapp</br>
√ Select a framework: » React</br>
√ Select a variant: » TypeScript</br>

Depois:</br>
cd meuapp</br>
`npm install`

Para usar Tauri é necessário ter Rust e algumas opções do Visual Studio Community instalados:</br>

https://www.rust-lang.org/learn/get-started</br>

https://visualstudio.microsoft.com/visual-cpp-build-tools/</br>

[<img alt="alt_text" width="600px" src="https://tauri.app/assets/images/vs-installer-dark-03cefd64bd4335f718aacc8f4842d2bb.png#gh-dark-mode-only" />](https://tauri.app/v1/guides/getting-started/prerequisites)

Instale o Tauri CLI: </br>
`cargo install tauri-cli`</br>

Após isso:</br>
`cargo tauri init`

Escolha as opções para o seu projeto</br>
Exemplo:</br>
✔ What is your app name? · meuapp</br>
✔ What should the window title be? · meuapp</br>
✔ Where are your web assets (HTML/CSS/JS) located, relative to the "<current dir>/src-tauri/tauri.conf.json" file that will be created? · ../dist</br>
✔ What is the url of your dev server? · http://localhost:5173</br>
✔ What is your frontend dev command? · npm run dev</br>
✔ What is your frontend build command? · npm run build</br>

Se quiser rodar o projeto no navegador use:</br>
`npm run dev`

Para abrir como janela:</br>
`cargo tauri dev`

Para gerar o app instalável:</br>

Windows Installer:</br>
`cargo tauri build`

Para agrupar todas as [licenças](https://crates.io/crates/cargo-bundle-licenses) "THIRDPARTY.yml" de terceiros em um único arquivo:</br>
`cargo install cargo-bundle-licenses`
