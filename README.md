https://github.com/user-attachments/assets/7564c3be-77e2-4283-a5ad-88ff973a269b

## Jev workflow builder

This demo shows you how to implement a multiplayer workflow builder for Jev with [Liveblocks](https://liveblocks.io/).
Hook together Jev and LLMs, use the REST API to call the workflow, preview test runs, see multiplayer state and cursors.

### Set up Liveblocks

- Install all dependencies with `npm install`
- Create an account on [liveblocks.io](https://liveblocks.io/dashboard)
- Copy your **secret** key from the [dashboard](https://liveblocks.io/dashboard/apikeys)
- Create an `.env` file at the root and add your **secret** key as the `LIVEBLOCKS_SECRET_KEY` environment variable
- Create an account on [Typesafe.ai](https://typesafe.ai/)
- Copy your **API key** from the [console](https://console.typesafe.ai/keys) into the `TYPESAFE_API_KEY` environment variable
- Create an account on [Vercel](https://vercel.com)
- Copy your **AI gateway key** from the [dashboard](https://vercel.com/ai-gateway) into the `AI_GATEWAY_API_KEY` environment variable
- Run `npm run dev` and go to [http://localhost:3000](http://localhost:3000)
