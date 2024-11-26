# CAT2pt2
Setup Instructions
1. Clone the repository 
git clone "git@github.com:Dexecuting/CAT2pt2.git"
cd "CAT2pt2"
2.  Create a virtual environment
python  -m venv venv
venv\Scripts\activate
3. Install dependencies
pip install -r requirements.txt
4. Run the API server
python app.py

Endpoints documentation
POST /products
Description: Creates a new product.
Request:
Content-type, body
Response:
201 created
400 bad request

GET/products
Description
Response:
200 OK

Requirements File (requirements.txt)
Flask
requests

Manual Testing 
Use tools like Postman
