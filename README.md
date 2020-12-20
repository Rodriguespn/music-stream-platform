# music-stream-platform


#### start back-end
cd music-stream-platform/music_controller
python3 ./manage.py makemigrations
python3 ./manage.py migrate
python3 ./manage.py runserver

#### start front-end
cd music-stream-platform/music_controller/frontend
npm run dev
