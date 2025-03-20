# **Imagify  Project**  
A text-to-image conversion project with integrated payment functionality, built using the MERN stack and containerized using Docker.

## **📌 Features**
- User authentication and credit-based system  
- Image generation using Clipdrop API  
- Payment integration with Razorpay  
- Fully containerized using Docker  
- Uses MongoDB for data storage  

## **🚀 Technologies Used**
- **Frontend**: React.js  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Payment Gateway**: Razorpay  
- **Containerization**: Docker, Docker Compose  

## **📦 Docker Containerization**
This branch (`compose`) contains Docker support for the project. It has the following containers:
1. **Backend** (`server`) - Runs the Express.js backend  
2. **Frontend** (`client`) - Serves the React.js frontend  
3. **MongoDB** (`mongodb`) - Database container  

### **🔧 How to Run with Docker**
Make sure you have **Docker** and **Docker Compose** installed. Then, follow these steps:

1. Clone the repository and switch to the `compose` branch:  
   ```sh
   git clone -b compose https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Build and start the Docker containers:  
   ```sh
   docker-compose up --build
   ```

3. The application should now be running:
   - Frontend: **http://localhost:5173**
   - Backend: **http://localhost:4000**

4. To stop the containers, use:  
   ```sh
   docker-compose down
   ```

## **📜 License**
This project is open-source and available under the [MIT License](LICENSE).  

---

For any issues or feature requests, feel free to open an issue in the repository. 🚀
