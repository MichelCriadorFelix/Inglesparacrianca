# 🦄 Escola Divertida

Mini aplicativo para crianças de 6 anos em fase de alfabetização revisarem as provas da escola brincando. Matérias: 🇬🇧 Inglês, 🔬 Ciências e 🗺️ Geografia (e crescendo!). No painel inicial escolhe-se a matéria; dentro dela, os módulos com o conteúdo de cada prova.

## O que tem

**Inglês (7 módulos):** 🍎 Frutas · 🌈 Cores · 🔢 Números · 👗 Roupas · ✏️ Escola · ⚽ Futebol · 🐶 Animais

**Ciências (6 módulos):** 🌍 Terra e Céu · 🌸 Estações do Ano · 🌱 Seres Vivos · 💧 Recursos Naturais · 🐝 Úteis e Nocivos · 🦁 Domésticos e Selvagens

**Geografia (6 módulos):** 🏫 Lugares da Escola · 🧑‍🏫 Profissionais da Escola · 👷 Construção de uma Casa · 💛 Cuidando da Escola · ✏️ Material Escolar · 🇧🇷 Brasil e a Bandeira

**4 atividades em cada módulo:**

| Atividade | O que faz |
|---|---|
| 📖 **Aprender** | Cartões grandes com figura, a palavra em inglês, a tradução e a dica de pronúncia "fala assim" escrita do jeito que se fala (ex.: APPLE → "É-pôu"). Botão 🔊 para ouvir e 🐢 para ouvir bem devagar. |
| 🎤 **Falar** | A criança fala no microfone e o app reconhece a voz (em inglês). Se acertou: festa e estrela ⭐. Se errou: mostra o que ela disse, repete a dica de pronúncia e toca a palavra devagarinho para ela tentar de novo. |
| ✍️ **Montar** | A criança monta a palavra tocando nas letras embaralhadas, na ordem certa — igual ao exercício de escrever da prova. Errou 2 vezes? A letra certa pisca em amarelo para ajudar. |
| 🎮 **Jogar** | Quiz com 8 perguntas misturadas (ouvir e escolher a figura, ver a figura e escolher a palavra, ler a palavra e escolher a figura). Ganha até 3 estrelas por jogo, com confete e sons de comemoração. |

O progresso (estrelas) fica salvo no aparelho.

## Como usar

🌟 **App no ar:** https://michelcriadorfelix.github.io/inglesparacrianca/

Toda vez que este repositório recebe uma atualização na branch `main`, o GitHub Pages republica o site automaticamente (veja `.github/workflows/deploy.yml`).

Também dá para usar sem internet: baixe o `index.html` e abra com o **Google Chrome** no computador.

> 🎤 **Importante:** o reconhecimento de voz (modo Falar) funciona no **Google Chrome** (computador e Android). Na primeira vez, toque em "Permitir" quando o navegador pedir o microfone. Os modos Aprender e Jogar funcionam em qualquer navegador.

> 📱 **Dica:** no celular, abra o site no Chrome → menu ⋮ → **"Adicionar à tela de início"** — vira um ícone como um aplicativo de verdade.

## Dicas para os pais

- Comece pelo módulo da prova (Frutas) no modo **Aprender**, depois **Falar**, depois **Jogar**.
- A dica amarela "fala assim" mostra a pronúncia escrita em português — ajuda quem ainda está aprendendo a ler.
- O botão 🐢 fala bem devagar — ótimo para treinar palavras difíceis como *strawberry*.
- Errar faz parte! O app nunca briga: ele mostra o que ouviu e ensina a falar certo.

## Tecnologia

HTML + CSS + JavaScript puro, em um único arquivo. Usa a Web Speech API do navegador (síntese e reconhecimento de voz) — sem servidor, sem cadastro, sem custo.
