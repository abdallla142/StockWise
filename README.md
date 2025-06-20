

##  Get Started

To use StockWise, just follow these quick steps:

1.  **Get the Code:**

    ```bash
    git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
    cd YOUR_REPO_NAME
    ```

    (Replace with your GitHub details.)

2.  **Open in Browser:** Double-click `index.html` in your file explorer.

3.  **Add API Key:**

      * **Finnhub (Stocks):** Sign up at [finnhub.io](https://finnhub.io/) for a free API key.
      * **CoinMarketCap (Crypto Current Prices):** Get a free Basic API Key from [pro.coinmarketcap.com/account/](https://pro.coinmarketcap.com/account/).
      * Open `index.html` in a text editor. Find the `FINNHUB_API_KEY` and `COINMARKETCAP_API_KEY` lines near the bottom. Replace the placeholder values with your keys:
        ```javascript
        const FINNHUB_API_KEY = 'YOUR_FINNHUB_API_KEY_HERE';
        const COINMARKETCAP_API_KEY = 'YOUR_COINMARKETCAP_API_KEY_HERE';
        ```
      * **Save** the file.

4.  **Reload:** Refresh your browser.

-----

##  How to Use

  * Use the **"Stocks"** and **"Crypto"** buttons to switch pages.
  * Type a symbol (like `AAPL` or `BTC`) in the search box and click **"Get Info"**.
  * The **AI chatbot** (bottom right) can answer general finance questions and give quick price looks.
  * Find external resources under "Beginner Investor Resources" and "Useful Financial Tools" at the bottom of the page.

-----

## Important Notes

  * **API Keys:** For real websites, **never show your API keys** like this. A server is needed to keep them safe.
  * **Free API Limits:** Free versions of these APIs have limits. Stock charts might show simulated data if live historical data isn't available. Crypto charts are always simulated.
  * **Crypto Price Accuracy:** Cryptocurrency prices in the app are **estimates** based on recent averages, not always live. A paid API is needed for real-time crypto charting and full accuracy.
  * **No Financial Advice:** This app is just for learning and showing how things work. It doesn't give financial advice.

-----
## Discalimer

This readme.md was creared by AI along with using AI for inspiration, I coded the project by myself and hope you enjoy it!

Data from [Finnhub.io](https://finnhub.io/) (stocks) and [CoinMarketCap](https://coinmarketcap.com/) (current crypto prices).
