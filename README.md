# cmpe-287-stock-portfolio

# Stock Portfolio Suggestion Engine

## Project Description

The Stock Portfolio Suggestion Engine utilizes various investment strategies, such as ethical investing, value investing, growth investing, index investing, and quality investing. It suggests optimal investment options based on the user's input of the investment amount. The user interface presents a detailed report of the recommended stock portfolio, providing a seamless experience.

### Features

1. User inputs the investment amount in USD (Minimum: $5000 USD).
2. Users can choose one or two investment strategies from the following options:
    - Ethical Investing
    - Growth Investing
    - Index Investing
    - Quality Investing
    - Value Investing
3. The engine assigns specific stocks or ETFs for the selected investment strategy. For example:
4. Index Investing strategy could map to ETFs like:
    - Vanguard Total Stock Market ETF (VTI)
    - iShares Core MSCI Total Intl Stk (IXUS)
    - iShares Core 10+ Year USD Bond (ILTB)
5. Ethical Investing strategy might map to individual stocks like:
    - Apple (AAPL)
    - Adobe (ADBE)
    - Nestle (NSRGY)
6. Each strategy corresponds to at least three different stocks or ETFs.
7. The suggestion engine provides:
    - The selected stocks based on inputted strategies.
    - Allocation of funds to purchase the suggested stocks.
    - Real-time values of the overall portfolio (updated regularly).
    - A weekly trend of the portfolio value, including a 5-day history.



### Running the Backend
1. Navigate to the `backend` directory:

    ```bash
    cd backend
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask app:

    ```bash
    python stock-suggestion-server.py
    ```

   The backend server should be running at http://127.0.0.1:5000

### Running the Frontend
1. Navigate to the `frontend` directory:

    ```bash
    cd frontend
    ```

2. Install the required dependencies:

    ```bash
    npm install
    ```

3. Start the React app:

    ```bash
    npm start
    ```

   The frontend should be accessible at http://localhost:3000.

Open your web browser and visit http://localhost:3000 to interact with the Stock Portfolio Suggestion Engine.


### Demo of the App

![App Demo](https://github.com/shiva-vardhineedi/cmpe-287-stock-portfolio/blob/main/results-thumbnail.PNG)

[YouTube video](https://www.youtube.com/watch?v=ho13C6_qh94)


### Team Members

- Siva Swaroop Vardhineedi
- Mahek Virani
- Varun Papishetty
- Gaurav Sarkar
