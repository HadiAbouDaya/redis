# Redis Inventory/Payment project

Build the react app:</br>
cd inventory-frontend
npm run build

Run the project:

First terminal:
cd inventory
uvicorn main:app --reload --port 8000

Second terminal:
cd payment
uvicorn main:app --reload --port 8001

third terminal:
cd inventory-frontend
npm start
