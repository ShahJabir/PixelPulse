# PixelPulse - 2D Metaverse Game

PixelPulse is a Zep.us-inspired 2D metaverse where users can explore a pixel-art world, chat, send messages, and make video calls. Built with a modern tech stack—NextJS, NodeJS/ExpressJS, MongoDB with Prisma, WebSockets/WebRTC, NX monorepo, Docker, and GitHub Actions—this project delivers a scalable, real-time social experience. Join our open-source community to contribute to the future of virtual spaces!

## Features
- **Explore**: Navigate a vibrant 2D pixel-art world
- **Chat**: Real-time text and voice messaging via WebSockets
- **Video Calls**: Seamless peer-to-peer video calls with WebRTC
- **Customizable Avatars**: Personalize your in-game presence
- **Scalable Backend**: Powered by NodeJS, ExpressJS, and MongoDB
- **Dev-Friendly**: NX monorepo and Docker for streamlined workflows

## Tech Stack
- **Frontend**: NextJS
- **Backend**: NodeJS, ExpressJS
- **Database**: MongoDB with Prisma ORM
- **Real-Time**: WebSockets, WebRTC
- **Monorepo**: NX
- **DevOps**: Docker, GitHub Actions for CI/CD

## Getting Started

### Prerequisites
- Node.js (>= 18.x)
- Docker
- MongoDB
- Git

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/pixelpulse.git
   cd pixelpulse
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Copy `.env.example` to `.env` and configure your settings (e.g., MongoDB URI, WebRTC configs).
4. Run with Docker:
   ```bash
   docker-compose up --build
   ```
5. Access the app at `http://localhost:3000`.

### Local Development
- Run the NextJS frontend: `nx run frontend:dev`
- Run the ExpressJS backend: `nx run backend:dev`

## Contributing
We welcome contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on code style, pull requests, and issues. Fork the repo, make your changes, and submit a PR to join the PixelPulse community.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact
For questions or feedback, open an issue or reach out via [GitHub Discussions](https://github.com/<your-username>/pixelpulse/discussions).

🚀 Let's build the ultimate 2D metaverse together!
