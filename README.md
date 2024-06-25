## WaveHack Global 2024

### 📺 Explanation / 説明書き

AI Agentsは、MetaMeプラットフォームにおけるエンゲージメントとコミュニティ活動を活性化するため、高度なAI機能を備えたiNFT（intelligence NFT）を開発します。これにより、メタバース内のインタラクションが豊かになり、ユーザー参加型のコンテンツ生成を促進します。

 [Web アプリ](https://aqvn7purek.ap-northeast-1.awsapprunner.com/)

 [Movie in Loom/ 紹介動画 Loom](https://www.loom.com/share/6d470c31cb374f7f94587d5b7be31d77?sid=c83495ec-9e79-43f2-96cd-7337bb9681b0)
  
### 🔵 How to excute / 実行方法
① Get API / APIの取得

.env.sample を .envに書き換えてください

  [NEXT_PUBLIC_ALCHEMY_API_KEY](https://www.alchemy.com/)
  
  [NEXT_PUBLIC_WEB3_AUTH_CLIENT_ID](https://web3auth.io/)

  [OPEN_WEATHER_API_KEY](https://hibi-update.org/other/openweathermap-api/)
  
  [OPENAI_API_KEY](https://platform.openai.com/api-keys)

  [CMC_API_KEY](https://coinmarketcap.com/api/)
  
  VOICEVOX_URL
  http://127.0.0.1:50021

② Starting Docker / Dockerの起動
```bash
docker-compose up
```

③ Starting Frontend /フロントエンドの起動
```bash
# Clone the repository
git clone git@github.com:lodestar3/frontend.git

# Change to the project directory
cd frontend

# Install library
npm install 

# Start the development server
npm run dev
```

### 🔵 Technical Challenges / 技術的挑戦

①ERC6551を用いた

②LLMシステム
