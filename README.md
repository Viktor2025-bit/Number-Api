# 📌 Number Classification API 🚀  
A Node.js API that classifies numbers based on mathematical properties and provides fun facts.

## 🛠 Features
- 🔢 **Prime Check** - Determines if a number is prime.
- 💯 **Perfect Number Check** - Identifies perfect numbers.
- 🎯 **Armstrong Number Check** - Checks if a number is an Armstrong number.
- 🔄 **Even/Odd Classification** - Determines if a number is even or odd.
- ➕ **Digit Sum Calculation** - Computes the sum of the number's digits.
- 🤓 **Fun Fact** - Retrieves a fun fact from the [Numbers API](http://numbersapi.com/).

## 📂 Project Structure
```
/number-classification-api
│── index.js          # Main server file
│── package.json      # Project dependencies
│── README.md         # Documentation
```

## 🛠 Installation
1. Clone the repository:
   ```sh
   git clone <your-github-repo-url>
   cd number-classification-api
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the server:
   ```sh
   npm run start 
   ```

4. Test the API locally:
   ```
   http://localhost:3000/api/classify-number?number=323
   ```

## 📡 API Endpoints
### 🔹 GET /api/classify-number
#### Request Example
```
GET /api/classify-number?number=700
```

#### Successful Response (200 OK)
```json
{
   "number": 700,
"is_prime": false,
"is_perfect": false,
"properties": [
"even"
],
"digit_sum": 7,
"fun_fact": "700 is the number of symmetric 8-cubes."
}
```

#### Error Response (400 Bad Request)
```json
{
    "number": "alphabet",
    "error": true
}
```

## 🚀 Deployment
This API is **publicly accessible** on **Render**:  
🔗 [Live API URL](https://your-api.onrender.com)  

## 📝 License
This project is open-source and available under the **MIT License**.
