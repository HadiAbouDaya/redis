# Redis Inventory/Payment project

Build the react app:</br>
cd inventory-frontend</br>
npm run build</br>

Run the project:</br>

First terminal:</br>
cd inventory</br>
pip install -r requirements.txt</br>
uvicorn main:app --reload --port 8000</br>

Second terminal:</br>
cd payment</br>
pip install -r requirements.txt</br>
uvicorn main:app --reload --port 8001</br>

third terminal:</br>
cd inventory-frontend</br>
npm start
