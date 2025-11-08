# chat_app
- let's say give a try to build a simple chat app (dont' u)
- currently it's just a basic django starter project template(moderate), Things will be updated soon:3  

## ⚙️ Local Setup
1. **Clone & Navigate**
```bash
git clone git@github.com:PritomKarmokar/chat_app.git
cd chat_app
```
2. **Copy `.env.example` to `.env`**
```bash
cp .env.example .env # Update `.env` with DB credentials & secret key
```
3. **Create & Activate a Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
4. **Install Dependencies**
```bash
pip install -r requirements.txt 
```
5. **Database & Server**
```bash
python manage.py migrate
python manage.py runserver
```
6. **(Optional) Create Admin & Run Tests**
```bash
python manage.py createsuperuser
python manage.py test
```