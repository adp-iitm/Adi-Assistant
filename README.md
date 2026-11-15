# 🚀 Adi Assistant

### Your AI-Powered Full-Stack Development Companion

Build, create, debug, and deploy applications using AI — all from your browser.

**Adi Assistant** is an AI-powered coding environment that brings multiple LLM providers into one development workspace. Choose your preferred AI model, describe what you want to build, and turn ideas into working applications.

---

## ✨ Features

- **AI-Powered Development:** Build full-stack Node.js applications directly in your browser.
- **Multiple AI Providers:** Connect OpenAI, Anthropic, Google Gemini, OpenRouter, Ollama, DeepSeek, Mistral, Groq, and more.
- **Flexible Model Selection:** Choose different AI models according to your development needs.
- **Image-to-Code:** Attach images to prompts for better visual understanding.
- **Integrated Terminal:** Execute commands and monitor their output.
- **Live Preview:** View your application as you build it.
- **Code Revisions:** Revert to earlier versions of your code.
- **Project Export:** Download your projects as ZIP files.
- **GitHub Integration:** Work with Git repositories and manage your projects.
- **Cloud Deployment:** Deploy projects through supported deployment integrations.
- **Custom API Endpoints:** Configure providers such as Ollama and LM Studio.

## 🛠️ Tech Stack

- React / TypeScript
- Vite
- Tailwind CSS
- Node.js
- WebContainers
- Vercel AI SDK
- Cloudflare Workers
- pnpm

## 🚀 Getting Started

### Prerequisites

Install the following:

- [Node.js](https://nodejs.org/) (LTS version)
- [pnpm](https://pnpm.io/)
- [Git](https://git-scm.com/)

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/adp-iitm/Adi-Assistant.git
cd Adi-Assistant
```

**2. Install dependencies**

```bash
pnpm install
```

**3. Start the development server**

```bash
pnpm run dev
```

**4. Open the application**

Visit:

```text
http://localhost:5173
```

## 🔑 AI Provider Configuration

Adi Assistant supports multiple AI providers.

Depending on your provider, you can configure API credentials directly through the application interface.

Supported providers include:

- OpenAI
- Anthropic
- Google Gemini
- OpenRouter
- Ollama
- LM Studio
- DeepSeek
- Mistral
- Groq
- xAI
- Hugging Face
- AWS Bedrock
- And other compatible providers

**Security:** Never commit actual API keys, passwords, or private credentials to GitHub.

## 📦 Available Commands

| Command | Description |
|---|---|
| `pnpm install` | Install dependencies |
| `pnpm run dev` | Start development server |
| `pnpm run build` | Build production application |
| `pnpm run start` | Run built application |
| `pnpm run preview` | Preview production build |
| `pnpm test` | Run test suite |
| `pnpm run typecheck` | Run TypeScript checks |
| `pnpm run typegen` | Generate Wrangler types |
| `pnpm run deploy` | Deploy to Cloudflare Pages |
| `pnpm run lint:fix` | Fix linting issues |

## 🐳 Docker Setup

Adi Assistant also supports Docker-based development.

Build the Docker image:

```bash
npm run dockerbuild
```

Or:

```bash
docker build . --target bolt-ai-development
```

Start the development container:

```bash
docker compose --profile development up
```

## 📁 Project Structure

```text
Adi-Assistant/
├── app/                  # Main application
├── functions/            # Cloudflare functions
├── public/               # Static assets
├── docs/                 # Documentation
├── icons/                # Provider and technology icons
├── package.json          # Dependencies and scripts
├── pnpm-lock.yaml        # Dependency lockfile
├── vite.config.ts        # Vite configuration
├── wrangler.toml         # Cloudflare configuration
└── README.md             # Project documentation
```

## 🤝 Contributing

Contributions, ideas, and improvements are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Test your implementation.
5. Submit a pull request.

## 🔐 Security

- Keep API keys private.
- Never commit `.env` files containing credentials.
- Use environment variables for sensitive configuration.
- Report security vulnerabilities responsibly.

## 📜 License

This project retains the licensing terms of its upstream components.

The original bolt.diy source code is distributed under the MIT License. WebContainers API usage may require a separate commercial license for qualifying production use.

Please review the applicable upstream licenses and terms before commercial deployment.

---

## 👨‍💻 Developer

**Adi Assistant**

Created and maintained by **Aditya Pareek**.

- GitHub: [@adp-iitm](https://github.com/adp-iitm)
- Project Repository: [Adi-Assistant](https://github.com/adp-iitm/Adi-Assistant)

---

<p align="center">
  <b>Built with ❤️ and AI.</b>
  <br/>
  Turning ideas into applications, one prompt at a time.
</p>