# Zenchain-nft
🧩 ZenChain x ZyNFT Portfolio 🚀 About This Project This is a sample portfolio built using the ZyNFT Marketplace on ZenChain Testnet. It demonstrates how to create, list, and showcase your NFTs using ZenChain's cutting-edge infrastructure.
# 🧩 Zynft Portfolio – ZenChain NFT Showcase

This is a React-based NFT portfolio viewer for the **ZyNFT Marketplace** on **ZenChain Testnet**. 
It allows users to connect their wallet, view owned NFTs, and interact with ZenChain using Web3.

---

## 📸 Preview
![Zynft Banner](public/banner.png)

---

## 🗂️ Folder Structure
```
/zynft-portfolio
├── public/                  # Static assets (e.g. logo, placeholder image)
│   ├── placeholder.png
│   └── banner.png           # Open Graph / project banner
├── src/                     # Main application source
│   ├── components/          # Reusable UI components (Navbar, NFTCard, etc.)
│   ├── pages/               # Page-level components (Home, Portfolio)
│   ├── utils/               # Utility functions (wallet, API calls)
│   ├── assets/              # Images, icons, branding assets
│   └── App.jsx              # Main App component
├── .env                     # Environment variables (e.g., RPC URL)
├── .gitignore               # Git ignored files
├── tailwind.config.js       # Tailwind CSS config
├── postcss.config.js        # PostCSS config
├── package.json             # Project metadata and dependencies
└── README.md                # Project introduction and setup instructions
```

---

## 🚀 Features
- Connect MetaMask wallet on ZenChain Testnet
- Fetch and display user-owned NFTs from ZyNFT Marketplace
- Responsive grid layout with NFT images, names, and descriptions
- Built with React + Tailwind CSS for clean and fast UI
- Easy to deploy on Vercel or Netlify

---

## 🛠 Tech Stack
- React.js / Tailwind CSS
- Web3.js / ZenChain RPC
- ZyNFT API (mock or real)
- Vercel or Netlify (for deployment)

---

## ⚙️ Getting Started
```bash
git clone https://github.com/your-username/zynft-portfolio.git
cd zynft-portfolio
npm install
npm run dev
```

> ⚠️ Make sure to set your `.env` file with the correct ZenChain RPC URL and ZyNFT API base URL.

Example `.env` file:
```env
VITE_RPC_URL=https://rpc.zenchain-testnet.org
VITE_ZYNFT_API=https://api.zynft.xyz
```

---

## 🌍 Deployment
You can easily deploy this project using:
- [Vercel](https://vercel.com/)
- [Netlify](https://netlify.com/)

After deployment, set the environment variables in the platform's dashboard.

---

## 🧪 Testing with Dummy Data
If the real ZyNFT API is unavailable, you can test with dummy NFT JSON like:
```json
[
  {
    "name": "Banana Warrior",
    "image": "/placeholder.png",
    "description": "Strong and sweet NFT on ZenChain"
  },
  {
    "name": "Avocado Hero",
    "image": "/placeholder.png",
    "description": "Full of healthy fats and style"
  }
]
```

---

## 🤝 Contribution
Pull requests are welcome! For any ideas or fixes, feel free to fork this repo and submit a PR.

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

---

## 📫 Contact
For questions, feedback, or collaboration:
📩 Email:mdshakibhossen304@gmail.com  
🌐 Twitter: [@MDshakibHo36524](https://twitter.com/MDShakibHo36524)

---

**Built with ❤️ for the ZenChain community.**
