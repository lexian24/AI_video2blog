# 📝 AI YouTube Blog Generator

This `Django` web application allow users to generates blog posts from YouTube videos. Users can log in, provide a YouTube link, and get a complete blog post generated from the video content. The app uses AssemblyAI for audio transcription and OpenAI for blog content generation.

<img width="1375" alt="Screenshot 2024-11-06 at 4 17 11 PM" src="https://github.com/user-attachments/assets/e0438365-2237-4eeb-8401-36785cc58c28">

## 🚀 Features

- **User Authentication**: Sign up, log in, and log out.
- **Blog Generation**: Converts YouTube videos into blog articles using `OpenAI API`.
- **Blog Management**: View and manage past generated blogs using database `Sqlite`.



## 📦 How to use it?

1. Clone the Repository
git clone https://github.com/your-username/YouTube-Blog-Generator.git
cd YouTube-Blog-Generator

3. Install Dependencies
pip install -r requirements.txt

4. Set Up API Keys
Create a .env file in the root directory and add your API keys for AssemblyAI and OpenAI:
ASSEMBLYAI_API_KEY=your-assemblyai-api-key
OPENAI_API_KEY=your-openai-api-key

5. Set Up Database
Run the following commands to set up the SQLite database:
python manage.py makemigrations
python manage.py migrate

6. Run the Server
Start the Django development server:
python manage.py runserver

Visit http://127.0.0.1:8000 to access the app.
