# Video Downloader App

This project is a Video Downloader that supports downloading videos from various platforms using different qualities. It consists of two main parts:

1. **Backend**: Built with Django and yt-dlp for handling video information and downloads.
2. **Frontend**: Built with React.js for a seamless user interface.

---

## Features

### Backend:
- Extract video details and available qualities using `yt-dlp`.
- Filter video qualities and return only allowed resolutions.
- Download videos based on user-selected quality.
- Use Django REST Framework for API handling.

### Frontend:
- Search for videos by URL.
- Display video thumbnail and available download qualities.
- Allow users to select and download videos in their preferred quality.
- User-friendly interface with error handling.

---

## Installation

### Clone Repository
1. Clone the Repository:
   ```bash
   git clone https://github.com/HariPasapuleti/Youtube_Video_Downloader.git
   ```
2. Navigate to the Project Directory
   ```bash
   cd Youtube_Video_Downloader
---

## Backend Setup
1. Navigate to the backend folder:
   ```bash
   cd backend
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. Start the backend server:
   ```bash
   python manage.py runserver
   ```

---

## Frontend Setup
1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the frontend server:
   ```bash
   npm run dev
   ```

---

## Usage
1. Open the application in your browser at `http://localhost:5173/`.
2. Enter a video URL and click `Search`.
3. Select a quality from the available options.
4. Click `Download Video` to download your selected video.

---

## Technologies Used

- **Frontend**: React.js, CSS
- **Backend**: Django, Django REST Framework, `yt-dlp`
- **API Communication**: Fetch API

