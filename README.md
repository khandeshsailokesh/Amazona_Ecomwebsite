
# This project is all about building a Ecom Website similar to Amazon.
![amazona](https://user-images.githubusercontent.com/53443055/218458924-cdaab309-124e-4146-a178-7c1dd4a70eec.jpg)

# Website Link
 👉 Render : https://amazona.onrender.com

 # Run Locally
  ### 1. Clone repo
  ```bash
  $ git clone https://github.com/khandeshsailokesh/Amazona_Ecomwebsite.git
  $ cd mern-amazona
```
### 2. Create .env File
- duplicate .env.example in backend folder and rename it to .env

### 3. Setup MongoDB
- Local MongoDB
   * Install it from here
   * In .env file update MONGODB_URI=mongodb://localhost/amazona
- OR Atlas Cloud MongoDB
   * Create database at https://cloud.mongodb.com
   * In .env file update MONGODB_URI=mongodb+srv://your-db-connection

### 4. Run Backend
```bash
 $ cd backend
 $ npm install
 $ npm start
```

### 5. Run Frontend
```bash
 # open new terminal
 $ cd frontend
 $ npm install
 $ npm start
```

### 6. Seed Users and Products
- Run this on browser: http://localhost:5000/api/seed
- It returns admin email and password and 6 sample products

### 7. Admin Login
- Run http://localhost:3000/signin
- Enter admin email and password and click signin


  


