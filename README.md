
# Blogopedia 📝

Welcome to Blogopedia, a dynamic and user-friendly blog application designed to foster creativity and engagement. This platform allows users to explore a variety of blog posts, leave comments, and interact with engaging content. Blogopedia prioritizes a seamless user experience with a responsive design and intuitive interface. While currently, only the admin can create, update, and delete blog posts, plans are underway to introduce these functionalities for all users, making it a truly collaborative blogging environment.

### Access the live application here: [Blogopedia](https://blogopedia-ten.vercel.app/)


## Features

- **User Authentication:** Secure user registration and login system.
- **Admin Privileges:** Admin can create, edit, and delete blog posts.
- **Post Management:** Users can view posts, while logged-in users can leave comments.
- **Responsive Design:** Optimized for various devices using Bootstrap.
- **Gravatar Integration:** Automatically fetches user avatars for comments.


## Built With 🛠️
- **Backend:** Python (Flask Framework)
- **Frontend:** HTML, CSS, JavaScript (Bootstrap for styling)
- **Authentication:** Flask-Login
- **Rich Text Editor:** Flask-CKEditor
- **Hosting:** Vercel

## Setup Instructions ⚙️
1. **Clone the repository:**
```bash
https://github.com/PraveenNPatil07/Blogopedia.git
cd Blogopedia
```
2. **Install dependencies:**
```bash
pip install -r requirements.txt
```
3. **Set up environment variables:**
- FLASK_KEY: Your Flask app secret key.
- DB_URI: Your database URI for SQLAlchemy.
4. **Run the application:**
```bash
python main.py
```
5. **Access the app locally at** ` http://127.0.0.1:5001.`
## Usage Instructions 📖
1. **Register/Login:** Create an account or log in to access user-specific features.
2. **Explore Posts:** Browse through the blog posts listed on the homepage.
3. **Comment:** Logged-in users can comment on blog posts.
4. **Admin Features:** Admin (User ID = 1) can add, edit, and delete blog posts.
## File Structure 📂
```bash
Blogopedia/
│
├── templates/           # HTML templates
├── static/              # Static files (CSS, JS, Images)
├── forms.py             # Forms for authentication and posts
├── main.py              # Main application file
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
└── .env                 # Environment variables

```
## Current Limitations and Future Plans 🚀
- Limitations:
    - Currently, only the admin can create, update, and delete blog posts.
- Future Plans:
   - Add the ability for regular users to create, update, and delete their own posts.
