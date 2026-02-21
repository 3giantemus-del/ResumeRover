# ResumeRover - AI Resume Screening Tool

ResumeRover is an intelligent desktop application designed for managing and screening resumes using AI.

## Features

- **Job Management**: Create dedicated folders for different job positions.
- **AI Screening**: Upload resumes to get an instant suitability score and detailed reasoning.
- **Candidate Tracking**: View and manage all applicants for a specific role in one place.
- **Optimized for Desktop**: A clean, professional interface designed for PC users.

## Local Development

1.  **Install dependencies**:
    ```bash
    npm install
    ```

2.  **Run the development server**:
    ```bash
    npm run dev
    ```
    Open [http://localhost:9002](http://localhost:9002) in your browser.

3.  **Genkit UI**:
    To explore and test the AI flows:
    ```bash
    npm run genkit:dev
    ```

## Publishing to the Web

To share this app with others, use **Firebase App Hosting**:

1.  **Commit and Push**: Ensure your code is in a GitHub repository.
2.  **Connect to Firebase**:
    - Go to the [Firebase Console](https://console.firebase.google.com/).
    - Select **App Hosting** from the Build menu.
    - Click **Get Started** and connect your GitHub repository.
3.  **Automatic Deployment**: Firebase will automatically build and deploy your app every time you push to your main branch.
4.  **Custom Domain**: Once deployed, you can connect your own domain (e.g., `www.resumerover.com`) through the Firebase Hosting settings.

## Security Note

This app uses Google Gemini AI via Genkit. Ensure your `GOOGLE_GENAI_API_KEY` is set up in your deployment environment (e.g., in the App Hosting dashboard under Environment Variables).

