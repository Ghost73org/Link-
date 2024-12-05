curl https://api.commerce.coinbase.com/checkouts \
-H "X-CC-Api-Key: 95933bf8-ec6a-4273-882d-d25cf8b0729d


curl -X POScurl -X POST https://api.commerce.coinbase.com/charges/ \
-H "Content-Type: application/json" \receives 
-H "X-CC-Api-Key: YOUR_API_KEY" \95933bf8-ec6a-4273-882d-d25cf8b0729d
-d '{
      "name": "The Human Fund",
      "description": "Money for news time",
      "pricing_type": "fixed_price",
      "local_price": {
        "amount": "1.00",
        "currency": "USD"
      }
    }'
    curl https://api.commerce.coinbase.com/charges/<CHARGE_UUID> \
-H "X-CC-Api-Key: 
95933bf8-ec6a-4273-882d-d25cf8b0729d
