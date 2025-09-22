![Marinesia](https://db.marinesia.com/storage/v1/object/public/assets//marinesia-logo-dark-smooth.png)


# Marinesia - Marine API

**Marinesia** is a free-to-use, lightweight and modern API designed for maritime applications. It provides APIs that support real-time vessel tracking, historical movements, ship profile management, global port registry, and location-aware CCTV live streams.

- Portal: [https://marinesia.com](https://marinesia.com)
- Documentation: [https://docs.marinesia.com](https://docs.marinesia.com)






## Features

- Vessel location (AIS)
- Vessel profile with image
- Global port directory
- Live CCTV streaming from onboard locations


## Getting started

#### Get Latest Vessel Location by MMSI

```http
  GET https://api.marinesia.com/api/v1/vessel/${MMSI}/location/latest?key=${YOUR_API_KEY}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `MMSI` | `string` | **Required**. MMSI (Maritime Mobile Service Identity) |
| `YOUR_API_KEY` | `string` | **Required**. Your API key |




## Support and Feedback

- Support: https://buymeacoffee.com/syauqisabili
- Feedback: contact@marinesia.com
