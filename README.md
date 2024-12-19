# ![Minder Logo](./src/assets/images/logo-circle.png) Minder

Minder is a simple and elegant mood tracking app designed to help users log their emotions and track patterns over time. Built with React Native, Minder provides a seamless experience for iOS users, with future scalability in mind.

## Features

- **Mood Logging**: Choose from four predefined moods: Happy, Neutral, Sad, Anxious.
- **Mood Trends Visualization**: View your mood trends over time with intuitive charts.
- **User Authentication**: Secure login to keep your data private.
- **Daily Reminders** (Future): Get notified to log your mood daily.
- **Data Export** (Future): Export your mood logs for sharing or personal records.

## Tech Stack

### Frontend
- **React Native**: Framework for building native iOS apps using JavaScript and TypeScript.
- **Expo**: Simplified setup and development for React Native apps.
- **NativeWind**: Tailwind CSS utility classes for styling.

### Backend
- **Supabase**: PostgreSQL database, authentication, and real-time syncing.
- **Supabase Auth**: Secure user authentication with email/password support.

## Project Structure

```
Minder/
├── src/
│   ├── components/     # Reusable UI components
│   ├── screens/        # Mood tracker, Trends, Profile screens
│   ├── navigation/     # Navigation setup
│   ├── supabase.ts     # Supabase client setup
├── App.tsx             # Main app entry point
├── tailwind.config.js  # Tailwind CSS configuration
├── package.json        # Project dependencies and scripts
├── babel.config.js     # Babel configuration
```

## Installation

### Prerequisites
1. **Node.js**: Install [Node.js](https://nodejs.org/) (LTS recommended).
2. **Expo CLI**: Install Expo CLI globally:
   ```bash
   npm install -g expo-cli
   ```
3. **Xcode**: Install Xcode from the Mac App Store for iOS development.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ciaran-06/minder.git
   ```
2. Navigate to the project directory:
   ```bash
   cd minder
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   expo start
   ```

5. Open the app:
   - Scan the QR code in the Expo Go app on your iPhone.

## Environment Variables

Create a `.env` file in the root directory and add the following:

```env
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
```

Replace `your-supabase-url` and `your-supabase-anon-key` with the keys from your Supabase project.

## Usage

1. Log in or create an account.
2. Log your mood by selecting one of the four mood options.
3. View your mood trends on the Trends screen.

## Future Features

- **Daily Reminders**: Push notifications to remind users to log their mood.
- **Data Export**: Download mood logs in CSV format.
- **Custom Notes**: Add personal notes to each mood entry.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

### Contact

For questions or feedback, reach out to:
- **Name**: Ciaran Gaffney
- **Email**: s2698881@ed.ac.uk
- **GitHub**: [ciaran-06](https://github.com/ciaran-06)
