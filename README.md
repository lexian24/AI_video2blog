### YouTube Blog Generator

# A web application that generates blog posts from YouTube videos. Users can log in, provide a YouTube link, and get a complete blog post generated from the video content. The app uses AssemblyAI for audio transcription and OpenAI for blog content generation.

# Features

User Authentication: Sign up, log in, and log out.
Blog Generation: Converts YouTube videos into blog articles.
Blog Management: View and manage generated blogs.

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
