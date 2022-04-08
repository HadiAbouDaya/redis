# Redis Inventory/Payment project

Build the react app:</br>
cd inventory-frontend</br>
npm run build</br>

Run the project:</br>

First terminal:</br>
cd inventory</br>
uvicorn main:app --reload --port 8000</br>

Second terminal:</br>
cd payment</br>
uvicorn main:app --reload --port 8001</br>

third terminal:</br>
cd inventory-frontend</br>
npm start
