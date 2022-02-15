# React Crypto Price Tracker

![Project Image](/public/demo.png)

---

### Table of Contents

- [Description](#description)
- [How To Use](#how-to-use)
- [References](#references)
- [License](#license)
- [Author Info](#author-info)

---

## Description

Crypto Price Tracker was created for my own interest in the crypto space and learning purposes to better understand React. Real time live demo deployed with Firebase. Cryptocurrency data is pulled from CoinGecko API. Flexbox and BEM class name convention was used for styling compenents.

#### Technologies

- React
- CSS
- HTML

[Back To The Top](#react-crypto-price-tracker)

---

## How To Use

#### Installation

- `git clone https://github.com/trilamanila/react-crypto-price-tracker`
- `cd react-crypto-price-tracker`
- `npm install`

#### API Reference

```Javascript
useEffect(() => {
    axios
      .get(
        "https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=100&page=1&sparkline=false"
      )
      .then(res => {
        setCoins(res.data);
      })
      .catch(error => console.log(error));
  }, []);
```

[Back To The Top](#react-crypto-price-tracker)

---

## References

[Back To The Top](#react-crypto-price-tracker)

- Website - [Trilamanila](https://joncinpicol.com)

---

## License

MIT License

Copyright (c) [2022][joncin picol]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back To The Top](#react-crypto-price-tracker)

---

## Author Info

- Website - [Trilamanila](https://joncinpicol.com)

[Back To The Top](#react-crypto-price-tracker)
