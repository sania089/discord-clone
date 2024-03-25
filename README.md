# discord-clone
This is a repository for Fullstack Discord Clone: Next.js 13, React, Socket.io, Prisma, Tailwind, MySQL 

![Screenshot 2024-03-26 025343](https://github.com/hailhydra1/discord-clone/assets/87016129/e3fb90bb-5a5f-4834-8c55-853aedc7f80a)
![Screenshot 2024-03-26 025449](https://github.com/hailhydra1/discord-clone/assets/87016129/f8e3a236-06e1-477d-b4f9-c479d0581dff)
![Screenshot 2024-03-26 025356](https://github.com/hailhydra1/discord-clone/assets/87016129/c5b451eb-fd0a-44bd-8548-28d2120b30bf)
![Screenshot 2024-03-26 025417](https://github.com/hailhydra1/discord-clone/assets/87016129/bc49a69d-0117-4f2c-bf0c-ce6c136983a5)
![Screenshot 2024-03-26 025603](https://github.com/hailhydra1/discord-clone/assets/87016129/0fd30862-5103-4f0a-89b6-6b949b55b79e)
![Screenshot 2024-03-26 025625](https://github.com/hailhydra1/discord-clone/assets/87016129/0174df0d-3483-4890-9d5d-379af1f6e21b)
![Screenshot 2024-03-26 025640](https://github.com/hailhydra1/discord-clone/assets/87016129/6bbb8ed4-ace9-4c9e-bbfa-fa894ce12e36)
![Screenshot 2024-03-26 025707](https://github.com/hailhydra1/discord-clone/assets/87016129/0be5eef9-e4a8-41da-b2c0-6e9c6778228f)



Features:

- Real-time messaging using Socket.io
- Send attachments as messages using UploadThing
- Delete & Edit messages in real time for all users
- Create Text, Audio and Video call Channels
- 1:1 conversation between members
- 1:1 video calls between members
- Member management (Kick, Role change Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (tanstack/query)
- Server creation and customization
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsivity and mobile UI
- Light / Dark mode
- Websocket fallback: Polling with alerts
- ORM using Prisma
- MySQL database using Planetscale
- Authentication with Clerk

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone "repo link"
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=


DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

### Setup Prisma

Add MySQL Database (I used PlanetScale)

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
