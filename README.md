
# **Movie Blog - Laravel**

A **movie blog website** built using the Laravel framework that allows users to browse and review movies.

## **Features**
- User authentication (login/register).
- Add, edit, and delete movies.
- Movie reviews and ratings.
- Search functionality.
- Responsive design.
- Secure environment using `.env`.

---

## **Installation**

### **1. Clone the Repository**
```bash
git clone <repository-url>
cd movieblog
```

### **2. Install Dependencies**
- Install PHP dependencies:
  ```bash
  composer install
  ```
- Install Node.js dependencies:
  ```bash
  npm install
  ```

### **3. Set Up Environment**
- Duplicate the `.env.example` file and rename it to `.env`:
  ```bash
  cp .env.example .env
  ```
- Update the `.env` file with your database credentials and other configuration.

### **4. Generate Application Key**
```bash
php artisan key:generate
```

### **5. Run Migrations**
```bash
php artisan migrate
```

### **6. Seed Database (Optional)**
```bash
php artisan db:seed
```

### **7. Run Development Server**
```bash
php artisan serve
```
Visit the application at `http://127.0.0.1:8000`.

---

## **Usage**
- Access the site.
- Create an account or log in.
- Add, edit, or delete movies.
- Post reviews and rate movies.

---



---

## **Technologies Used**
- **Backend**: Laravel
- **Frontend**: Blade templates, CSS, JavaScript
- **Database**: MySQL
- **Package Manager**: Composer, NPM

---

## **Contributing**
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature-name'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

---


## **Contact**
For inquiries or suggestions, contact:
- **Email**: gauravrajput3005@gmail.com
- **GitHub**: [Gaurav](https://github.com/gaurav8299)
