# Weather BMKG API

![Weather BMKG Logo](./assets/wheather.png)

This project is an API for retrieving weather forecast data from the Indonesian Meteorological, Climatological, and Geophysical Agency (BMKG). It provides digital forecast data for various regions in Indonesia.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nandasafiqalfiansyah/weather-bmkg-api.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

## Usage

To start the server, you can use the following command:

```bash
npm start
```

Or if you prefer to run the server with auto-restart on file changes (using nodemon):

```bash
npm run dev
```

## Endpoints

The API provides the following endpoints:

- `/weather/?weather=:region`: Get weather forecast data for a specific region.

Replace `:region` with the desired region, e.g., `aceh`, `bali`, `jakarta`.

## Example

To retrieve weather forecast data for Jakarta, you can send a GET request to:

```
http://localhost:3000/weather?weather=jakarta
```

## List of Regions

| Region              | URL                                                                                                                                |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Aceh                | [DigitalForecast-Aceh.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-Aceh.xml)                           |
| Bali                | [DigitalForecast-Bali.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-Bali.xml)                           |
| Bangka Belitung     | [DigitalForecast-BangkaBelitung.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-BangkaBelitung.xml)       |
| Banten              | [DigitalForecast-Banten.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-Banten.xml)                       |
| Bengkulu            | [DigitalForecast-Bengkulu.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-Bengkulu.xml)                   |
| DIY Yogyakarta      | [DigitalForecast-DIYogyakarta.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-DIYogyakarta.xml)           |
| DKI Jakarta         | [DigitalForecast-DKIJakarta.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-DKIJakarta.xml)               |
| Gorontalo           | [DigitalForecast-Gorontalo.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-Gorontalo.xml)                 |
| Jambi               | [DigitalForecast-Jambi.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-Jambi.xml)                         |
| Jawa Barat          | [DigitalForecast-JawaBarat.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-JawaBarat.xml)                 |
| Jawa Tengah         | [DigitalForecast-JawaTengah.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-JawaTengah.xml)               |
| Jawa Timur          | [DigitalForecast-JawaTimur.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-JawaTimur.xml)                 |
| Kalimantan Barat    | [DigitalForecast-KalimantanBarat.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-KalimantanBarat.xml)     |
| Kalimantan Selatan  | [DigitalForecast-KalimantanSelatan.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-KalimantanSelatan.xml) |
| Kalimantan Tengah   | [DigitalForecast-KalimantanTengah.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-KalimantanTengah.xml)   |
| Kalimantan Utara    | [DigitalForecast-KalimantanUtara.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-KalimantanUtara.xml)     |
| Kepulauan Riau      | [DigitalForecast-KepulauanRiau.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-KepulauanRiau.xml)         |
| Lampung             | [DigitalForecast-Lampung.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-Lampung.xml)                     |
| Maluku              | [DigitalForecast-Maluku.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-Maluku.xml)                       |
| Maluku Utara        | [DigitalForecast-MalukuUtara.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-MalukuUtara.xml)             |
| Nusa Tenggara Barat | [DigitalForecast-NusaTenggaraBarat.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-NusaTenggaraBarat.xml) |
| Nusa Tenggara Timur | [DigitalForecast-NusaTenggaraTimur.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-NusaTenggaraTimur.xml) |
| Papua               | [DigitalForecast-Papua.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-Papua.xml)                         |
| Papua Barat         | [DigitalForecast-PapuaBarat.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-PapuaBarat.xml)               |
| Riau                | [DigitalForecast-Riau.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-Riau.xml)                           |
| Sulawesi Barat      | [DigitalForecast-SulawesiBarat.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-SulawesiBarat.xml)         |
| Sulawesi Selatan    | [DigitalForecast-SulawesiSelatan.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-SulawesiSelatan.xml)     |
| Sulawesi Tengah     | [DigitalForecast-SulawesiTengah.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-SulawesiTengah.xml)       |
| Sulawesi Tenggara   | [DigitalForecast-SulawesiTenggara.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-SulawesiTenggara.xml)   |
| Sulawesi Utara      | [DigitalForecast-SulawesiUtara.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-SulawesiUtara.xml)         |
| Sumatera Barat      | [DigitalForecast-SumateraBarat.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-SumateraBarat.xml)         |
| Sumatera Selatan    | [DigitalForecast-SumateraSelatan.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-SumateraSelatan.xml)     |
| Sumatera Utara      | [DigitalForecast-SumateraUtara.xml](http://data.bmkg.go.id/datamkg/MEWS/DigitalForecast/DigitalForecast-SumateraUtara.xml)         |

## Dependencies

- [async](https://www.npmjs.com/package/async): ^3.2.5
- [body-parser](https://www.npmjs.com/package/body-parser): ^1.20.2
- [cors](https://www.npmjs.com/package/cors): ^2.8.5
- [express](https://www.npmjs.com/package/express): ^4.18.2
- [nodemon](https://www.npmjs.com/package/nodemon): ^3.0.3
- [request](https://www.npmjs.com/package/request): ^2.88.2
- [xml2js](https://www.npmjs.com/package/xml2js): ^0.6.2

## buymeacoffee

<a href="https://www.buymeacoffee.com/nandasafiqx" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

## License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.
