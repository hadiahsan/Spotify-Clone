# spotify-clone
This project replicates the user interface of Spotify, utilizing Next.js and React to deliver a seamless user experience. Secure and dependable payment functionalities are integrated through Stripe, offering an upgraded premium service in the clone. The backend infrastructure uses Supabase and PostgreSQL, guaranteeing robust data management and scalable performance.


# Setup

**Node Version:** 14.x

1. **Cloning the Repository:**
   - Clone the project repository using the following command:
     ```
     git clone https://github.com/AntonioErdeljac/next13-spotify.git
     ```

2. **Install Packages:**
   - Navigate to the project directory and install the required packages with npm:
     ```
     npm i
     ```

3. **Setup Environment Variables:**
   - Create a `.env` file in the project directory and add the following variables:
     ```
     NEXT_PUBLIC_SUPABASE_URL=
     NEXT_PUBLIC_SUPABASE_ANON_KEY=
     SUPABASE_SERVICE_ROLE_KEY=

     NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
     STRIPE_SECRET_KEY=
     STRIPE_WEBHOOK_SECRET=
     ```

4. **Add SQL Tables:**
   - Use the `database.sql` file and follow the instructions provided in the associated video tutorial to create the `songs` and `liked_songs` tables.

5. **Start the App:**
   - Run the following command to start a development instance of the app:
     ```
     npm run dev
     ```

## Available Commands

You can run the following commands using npm:

- **dev:** Starts a development instance of the app

