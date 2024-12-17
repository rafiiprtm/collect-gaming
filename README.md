# 🎮 Collect Your GamingTools 🕹️
A <b> responsive and dynamic website </b> to showcase the best gaming accessories for every gamer!

## ✨ Features
🗂️ <b>Dynamic Navigation Menu</b>: Toggle visibility, designed for seamless use across all screen sizes.  

🛒 <b>Product Display</b>: View gaming products with prices, discounts, and a "Buy Now" option.

🌐 <b>Social Media Links</b>: Instant access to your favorite platforms like Facebook, Twitter, and Instagram. 

📱 <b>Responsive Design</b>: Enjoy smooth navigation whether you're on mobile, tablet, or desktop! 



## 💻 Technologies Used ( Frontend )
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js" />
  </a>
</p>

## 💻 Technologies Used ( Backend & Docker Functionality )

- 🟢 **Node.js** and **Express** for the backend
- 🍃 **MongoDB** for database storage
- 🐳 **Docker** for containerization

<p align="center">
    <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,docker" alt="Node.js, Express, MongoDB, Docker" />
    </a>
</p>

## ⚙️ Backend Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/rafiiprtm/collect-gaming.git
    ```
2. Install dependencies:
    ```bash
    cd collect-gaming
    npm install
    ```

3. Configure environment variables:
Create a .env file with:
```bash
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Start the server:
```bash
npm start
```

## 🐳 Docker
Build the Docker image:
```bash
docker build -t gamingtools-backend .
```

Run the container:
```bash
docker run -d -p 5000:5000 --env-file .env gamingtools-backend
```
## 🚀 Demo
#### Check out the live demo here ⬇️ : 

https://gamerium.vercel.app/

## 🛠️ Installation
#### To get started, simply clone the repository and open it in your browser:

1. Clone the repository:
    ```bash
    git clone https://github.com/rafiiprtm/collect-gaming.git
    ```
2. Navigate to the project directory:
    ```bash
    cd collect-gaming
    ```
3. Open the `index.html` file in your browser:
    ```bash
    open index.html  # On macOS
    start index.html # On Windows
    xdg-open index.html # On Linux
    ```
