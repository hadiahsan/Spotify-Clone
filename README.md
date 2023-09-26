# spotify-clone
This project replicates the user interface of Spotify, utilizing Next.js and React to deliver a seamless user experience. Secure and dependable payment functionalities are integrated through Stripe, offering an upgraded premium service in the clone. The backend infrastructure uses Supabase and PostgreSQL, guaranteeing robust data management and scalable performance.


#Setup

Node version 14.x

Cloning the repository
git clone https://github.com/AntonioErdeljac/next13-spotify.git
Install packages
npm i
Setup .env file
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
Add SQL Tables
Use database.sql file, create songs and liked_songs table (there is a video tutorial)

Start the app
npm run dev
Available commands
Running commands with npm run [command]

command	description
dev	Starts a development instance of the app
