Objective:
The goal of this project is to develop a simple website that allows users to convert currency values from various international currencies to VND (Vietnamese Dong) using real-time exchange rates.


Technologies Used:
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express (optional for API requests)
API: A currency conversion API (e.g., ExchangeRate-API, OpenExchangeRates)
Libraries: Axios (for API calls), Bootstrap (for design)


API Setup
a. Get an API Key:
Sign up for an API key from a currency conversion service like ExchangeRate-API or OpenExchangeRates.
ExchangeRate-API: Offers free tier with limited requests.
OpenExchangeRates: Another option, though it has a free and paid version.
b. Environment Variables:
Store your API key securely if using Node.js or any server-side framework. You can use environment variables or config files to hide the key.



Testing and Deployment
a. Test Locally:
Test the website on your local machine to ensure that the currency conversion works correctly, and the API fetches real-time rates.
b. Deploy:
Deploy the website using hosting platforms like GitHub Pages, Netlify, or Vercel. If a backend is used, services like Heroku or AWS can be good choices for deploying the server.