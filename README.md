# TcpNetworking

A lightweight and reusable C++ TCP networking library that provides a **TCP Server** and **TCP Client** with a common `Socket` class. This library allows easy integration of networking functionality into C++ projects without relying on external dependencies.

## 🚀 Features
- Simple and reusable **TCP Server** and **TCP Client** implementation.
- **Common `Socket` class** for easy extensibility.
- Supports Linux as of now
- Uses **CMake** for easy building and integration.
- Example programs included for quick testing.

## 📁 Project Structure
```sh
TcpNetworking/
│── include/
│   ├── Socket.h
│   ├── TcpServer.h
│   ├── TcpClient.h
│── src/
│   ├── Socket.cpp
│   ├── TcpServer.cpp
│   ├── TcpClient.cpp
│── examples/
│   ├── server_example.cpp
│   ├── client_example.cpp
│── CMakeLists.txt       # Root CMake file
│── examples/CMakeLists.txt  # Examples CMake file
│── LICENSE
│── README.md
```

## 🛠️ Installation & Usage

### **1. Clone the Repository**
```sh
git clone https://github.com/YOUR_USERNAME/TcpNetworking.git
cd TcpNetworking
```
### **2. Build the Project using CMake**
```sh
mkdir build && cd build
cmake ..
make
```
### **3. Run the Examples**
```sh
./examples/server_example
./examples/client_example
```

## 📩 Contact
Email: mmchinmay555@gmail.com
LinkedIn: https://www.linkedin.com/in/chinmay-rao-mm/

## 📝 License
This project is licensed under the MIT License. See the LICENSE file for details.
