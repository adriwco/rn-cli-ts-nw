Estrutura básica > uso pessoal > lembrete

npx react-native init AwesomeProject --template react-native-template-typescript
cd AwesomeProject

npm install nativewind
npm install --save-dev tailwindcss@3.3.2

npx tailwindcss init

// tailwind.config.js
module.exports = {
  content: ["./App.{js,jsx,ts,tsx}", "./<custom-folder>/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

nativewind-env.d.ts > /// <reference types="nativewind/types" />

ex: <Text className="text-2xl font-bold text-center">teste</Text>