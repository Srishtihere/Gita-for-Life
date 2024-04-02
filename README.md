<p align="center">
  <img style="border-width: 0" width="400" height="400" src="./src/assets/gfl-logo.png" alt="Gita For Life Logo">
</p>

# Gita For Life

Welcome to Gita-for-Life, your ultimate online resource for exploring the profound teachings of the Bhagavad Gita, along with captivating narratives from the Mahabharata and Ramayana epics. Immerse yourself in the timeless wisdom of ancient scriptures, as we delve into the essence of life, morality, and spirituality.

---

## Screenshots

### Mobile Device

<img src="./src/assets/Screenshots/mobile_ss_1.png" height='500px'>

<img src="./src/assets/Screenshots/mobile_ss_2.png" height='500px'>

<img src="./src/assets/Screenshots/mobile_ss_3.png" height='500px'>

### Laptop Device

<img src="./src/assets/Screenshots/desktop_ss_1.png" height='200px'>

<img src="./src/assets/Screenshots/desktop_ss_2.png" height='200px'>

<img src="./src/assets/Screenshots/desktop_ss_3.png" height='200px'>

<img src="./src/assets/Screenshots/desktop_ss_4.png" height='200px'>

## Tech/ Framework Used

- React
- TypeScript
- Axios
- Router
- React-Bootstrap
- Bootstrap
- Bhagwad Gita API

## Features

- <b>Bhagavad Gita Insights:</b> Delve into the sacred verses of the Bhagavad Gita, dissecting its philosophical depth and practical wisdom. Explore key concepts such as Dharma, Karma, and Yoga, accompanied by detailed explanations and interpretations.

- <b>Slokas Repository:</b> Access a comprehensive collection of slokas (verses) from the Bhagavad Gita, categorized for easy navigation. Dive deep into the profound meanings behind each verse, along with insights into their relevance in modern life.

- <b>Real-Life Lessons</b>: Discover how the teachings of the Bhagavad Gita transcend time and space, offering valuable insights for navigating the complexities of everyday life. Explore real-life scenarios and learn how to apply Gita's principles to overcome challenges and achieve inner peace.

- <b>Mahabharata Storyline:</b> Embark on a captivating journey through the epic tale of the Mahabharata, unraveling its intricate plotlines, legendary characters, and timeless lessons. From the righteous struggles of the Pandavas to the enigmatic wisdom of Lord Krishna, experience the saga like never before.

- <b>Ramayana Narrative:</b> Immerse yourself in the enchanting narrative of the Ramayana, filled with adventure, devotion, and moral dilemmas. Follow the heroic exploits of Lord Rama, Sita, Hanuman, and other iconic figures, while uncovering the profound moral lessons embedded within.

- <b>Conclusive Insights:</b> Reflect on the profound conclusions drawn from the Bhagavad Gita, Mahabharata, and Ramayana, synthesizing their teachings into actionable insights for modern life. Gain clarity on existential questions, ethical dilemmas, and the pursuit of spiritual fulfillment.

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
