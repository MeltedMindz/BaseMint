# BaseMint
https://basemint.art/

Generative Art Creation on Base Layer 2

## Project Overview

**BaseMint** is a generative art platform built on the **Base Layer 2** blockchain. The platform empowers artists to create, customize, and deploy their own generative art collections using pre-existing smart contracts, similar to Art Blocks and fxhash. By leveraging the scalability and low transaction fees of Base, **BaseMint** enables a cost-effective and user-friendly environment for artists to mint and sell their generative art directly on-chain.

### Key Features

- **Pre-Deployed Script Libraries**: Artists can access popular generative art libraries like **p5.js**, **Three.js**, and **GLSL** that are stored permanently on **Onchain**. These libraries provide the foundation for creating generative art without needing to write complex backend logic.
  
- **Boilerplate for Easy Customization**: Users can download a **boilerplate template** that includes references to Arweave-hosted libraries. Artists can modify the template locally to create their custom art and upload their final scripts back to the platform for minting.

- **Smart Contract Integration**: Once an artist uploads their custom generative art script, they can deploy their own **proxy contract** that points to the pre-existing base contract. The platform automatically collects 10% of primary sales, making it easy for artists to focus on creativity without managing contract details.

- **Testnet Deployment First**: The platform will first be tested on a testnet to ensure smooth functionality before launching on Base mainnet.

- **Fully On-Chain Art**: The platform uses a hybrid approach, where art scripts are stored on Arweave, and metadata is fully on-chain. This ensures permanent storage and accessibility of the generative art while keeping gas costs low for minting.

## How It Works

### 1. Choose or Upload Your Script
Artists can either:
- **Select from pre-deployed script libraries** like p5.js or Three.js to build their artwork, or
- **Download a boilerplate template**, customize it locally, and upload their own generative art script.

### 2. Customize and Upload
Using the platform’s **boilerplate template**, artists can easily create generative art by modifying the included JavaScript libraries. Once ready, they can upload their finalized scripts to the platform.

### 3. Deploy Your Art
After uploading the script, artists can deploy a smart contract (proxy) on Base Layer 2. The smart contract will store the Arweave reference to the script, allowing collectors to mint unique artworks generated on the blockchain.

### 4. Mint and Collect
Collectors can mint NFTs directly from the deployed contracts. Each mint generates a unique piece of generative art using the artist's script, and the platform collects a small commission from primary sales.

## Why BaseMint?

- **Affordable Minting**: By using Base Layer 2, gas costs are extremely low compared to Ethereum mainnet, making it accessible for both artists and collectors.
- **Pre-built Tools**: Artists can create without worrying about smart contract code or managing storage – BaseMint handles all backend operations.
- **Permanence**: The platform stores scripts on **Arweave**, ensuring that generative art is available permanently without the need for centralized storage or pinning services.
- **Scalability**: Designed to handle a large number of generative art projects while maintaining an intuitive and user-friendly interface.

### Roadmap

### Backend Development
- [ ] Implement Arweave storage for script libraries and user uploads.
- [ ] Build API endpoints for handling script uploads and downloads.
- [ ] Develop the smart contract for proxy contract deployment and minting.
- [ ] Set up testnet environment for contract testing (Base Goerli).

### Frontend Development
- [ ] Design and develop the user interface for uploading and selecting scripts.
- [ ] Integrate Arweave-hosted script libraries into the front-end UI.
- [ ] Build the boilerplate download feature for easy script customization.
- [ ] Implement the script upload form and integrate with backend for minting.
- [ ] Create a preview feature to allow artists to view their generative art before minting.
- [ ] Test the frontend workflow on the testnet with real contract interactions.

### Marketing and Community Building
- [ ] Launch a website to promote the platform and explain its features.
- [ ] Develop a content marketing strategy (e.g., blog posts, social media content).
- [ ] Build a community on Twitter, Discord, or other social platforms for artists and collectors.
- [ ] Partner with artists to showcase initial generative art projects and case studies.
- [ ] Plan a testnet beta launch to gather feedback from early users.
- [ ] Create educational materials (tutorials, videos) to onboard artists and developers.
  
## License

### Open-Source License (MIT)
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
### Trademark Notice

The name "Basemint.art", associated logos, and branding are trademarks of BaseMint, llc. You may not use the "BaseMint" name, logos, or branding in any commercial or non-commercial context without express written permission from the trademark holder.

Any attempt to create derivative works or forks that use the "Basemint.art" brand or associated marks is strictly prohibited. You are free to fork and modify the code under the terms of the open-source license, but must create a new name and brand for any such project.

For inquiries about trademark licensing or use of the Basemint.art brand, please contact Meltedmindz.
