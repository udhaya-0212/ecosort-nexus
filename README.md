# EcoSort Nexus

Smart waste segregation dashboard with live camera classification, bin fill monitoring, alerts, reports, hardware status, and an animated three-bin simulator.

## Run locally

Serve this folder over HTTP (camera access requires localhost or HTTPS):

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## AI model

The included TensorFlow.js model runs in the browser through `ai-worker.js`. It is trained for Paper, Cardboard, Plastic Bottle, Glass Bottle, Metal Can, Food Waste, Banana Peel, Apple, Chip Packet, and Mixed Covered Bag. No API key is needed for the included model. The optional cloud inference fields can be left blank.
