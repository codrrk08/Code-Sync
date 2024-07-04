# CodeSync

A real-time collaborative code editor with unique room generation, syntax highlighting, and auto-suggestions. Users can seamlessly edit, save, and download files while engaging in group chat for efficient communication.

## Installation

1) Fork this repository: Click the Fork button located in the top-right corner of this page to fork the repository.

2) Clone the repository:

```bash
git clone https://github.com/<your-username>/Code-Sync.git
```
3) Set .env file: Inside the client and server directories rename the .env.example file to .env and set the following environment variables:

  Frontend:
```bash
VITE_BACKEND_URL=<your_server_url>
```
   Backend:
```bash
PORT=3000
```
4) Install dependencies: Navigate to the frontend and backend directories separately and run:

 ```bash 
npm install
```
5) Start the frontend and backend servers:

Frontend:
```bash
cd client
npm run dev
```

Backend:
```bash
cd server
npm run dev
```
