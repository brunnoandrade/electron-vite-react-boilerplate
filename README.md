<div align="center" style="margin-top: 0;">
<img width="467" height="244" alt="Electron Vite React" src="https://github.com/user-attachments/assets/6faa94b9-1401-41a3-a0b1-51b07fd02b52" />
</div>

# Electron Vite React Boilerplate

🚀 A modern and minimal boilerplate to build desktop applications using **Electron**, **Vite**, **React**, and **TypeScript**.

Perfect for quickly starting scalable, fast, and cross-platform desktop apps with hot reload and a clean project structure.

---

## ⚙️ Technologies Used

* ⚡️ [Vite](https://vitejs.dev/)
* ⚛️ [React](https://reactjs.org/)
* 🧠 [TypeScript](https://www.typescriptlang.org/)
* 🖥️ [Electron](https://www.electronjs.org/)
* 📦 [Electron Builder](https://www.electron.build/)

---

## 🛠️ Getting Started

```bash
npx degit brunnoandrade/electron-vite-react-boilerplate my-app
cd my-app
npm install
npm run dev
```

---

## 📦 Commands

| Script    | Description                                                             |
| --------- | ----------------------------------------------------------------------- |
| `dev`     | Runs the application in development mode using Vite                     |
| `build`   | Compiles TypeScript, builds the Vite app, and packages it with Electron |
| `preview` | Previews the production build of the Vite app locally                   |
| `lint`    | Runs ESLint on all `.ts` and `.tsx` files with strict rules             |

> ℹ️ This boilerplate currently includes only the above commands. Other scripts like `start`, `test`, or `storybook` can be added as needed.

---

## 🧩 Project Structure

```
├── dist/                # Vite production build (React frontend)
├── dist-electron/       # Electron build output
├── electron/            # Electron main and preload source files
│   ├── main/
│   └── preload/
├── public/              # Static public assets
├── src/                 # React renderer application
├── vite.config.ts       # Vite configuration
└── package.json         # Project metadata and scripts
```

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contribution you make is **greatly appreciated**.

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📬 Contact

**Bruno Andrade**
📧 [brunnoandradi@gmail.com](mailto:brunnoandradi@gmail.com)
🔗 [GitHub](https://github.com/brunnoandrade)
🌐 [Website](https://brunnoandrade.com)
