# Weather Lucid Agent

x402-gated weather agent. Returns current conditions for any city.

> **Built via [TaskMarket](https://taskmarket.xyz) bounty**

## Live Endpoint
`GET https://arizona-pour-sauce-especially.trycloudflare.com/weather?location=London`

### 402 (no payment)
```bash
curl https://arizona-pour-sauce-especially.trycloudflare.com/weather?location=London
# HTTP 402 with x402 requirements
```

### 200 (with payment)
```bash
curl https://arizona-pour-sauce-especially.trycloudflare.com/weather?location=Madrid -H "X-Payment: <proof>"
```
```json
{"location":"Madrid, Spain","tempC":34,"tempF":93,"feelsLikeC":32,"humidity":14,"description":"Sunny","windKph":15,"visibility":10,"uvIndex":1}
```

## Details
- Network: Base Sepolia (eip155:84532) | Amount: 0.001 USDC
- Data: [wttr.in](https://wttr.in) (free) | Built via [TaskMarket](https://taskmarket.xyz)
