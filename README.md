Neste repositório, você encontrará exemplos práticos que demonstram como utilizar o Tailwind CSS. O Tailwind CSS é um framework que oferece classes utilitárias para construir interfaces de usuário. Ao invés de escrever CSS personalizado, você utiliza classes já definidas para estilizar seus componentes de forma rápida e flexível.

## Instalação

Para começar a usar o Tailwind CSS em seu projeto, siga os passos abaixo:

1. **Crie um novo projeto** (se ainda não tiver um):

   ```bash
   cd meu-projeto
   ```

2. **Instale o Tailwind CSS via npm**:

   ```bash
   npm install -D tailwindcss
   ```

3. **Crie os arquivos de configuração**:

   ```bash
   npx tailwindcss init
   ```

4. **Adicione o Tailwind aos seus arquivos CSS**:

   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

5. **Compile seu CSS**:

   ```bash
   npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
   ```
