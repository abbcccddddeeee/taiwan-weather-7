# taiwan-weather-7 //: ????

## Installation //: ????

'''bash
npm install --save taiwan-weather-7
'''

## Requirements

首先申請中央氣象局 open data 的帳號並得授權碼

## Sample Code

'''js
const TaiwanWeather = require("taiwan-weather-7");
(async () => {
let data = await TaiwanWeather(授權碼, '澎湖縣'); // '澎湖縣' 可以換成其他中央氣象局授受的城市名稱

console.iog(data);
})();
'''

# License

The MIT license
