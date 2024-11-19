curl https://api.commerce.coinbase.com/checkouts \
-H "X-CC-Api-Key: 746e77e5-c388-48b5-9865-9b0c6adc1959


curl -X POScurl -X POST https://api.commerce.coinbase.com/charges/ \
-H "Content-Type: application/json" \receives 
-H "X-CC-Api-Key: YOUR_API_KEY" \746e77e5-c388-48b5-9865-9b0c6adc1959
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
-H "X-CC-Api-Key: 746e77e5-c388-48b5-9865-9b0c6adc1959

