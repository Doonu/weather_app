# weather_app vue_js angular and react

next, react-query, (альтурнатив styled-components), (альтернеатива Antd)

OpenWeatherMap - Один из самых популярных бесплатных API, который предоставляет данные о текущей погоде, прогнозы на 5/16 дней, карты и многое другое.
Официальный сайт: OpenWeatherMap
Weather API - Этот API предоставляет данные о погоде в реальном времени, прогнозы, исторические данные и будущие прогнозы.
Официальный сайт: Weather API
AccuWeather - Предоставляет точные прогнозы и различные погодные данные с помощью своего API, но большинство функций платные.
Официальный сайт: AccuWeather API
Weatherstack - Этот API предлагает мгновенный доступ к текущей погоде, прогнозам и историческим погодным данным.
Официальный сайт: Weatherstack

Пример использования API OpenWeatherMap
Чтобы использовать OpenWeatherMap, вам сначала нужно зарегистрироваться на их сайте, чтобы получить API ключ. После этого вы можете делать запросы к API. Вот пример запроса на получение текущей погоды:

http
Copy code
GET http://api.openweathermap.org/data/2.5/weather?q=London&appid=your_api_key
Как сделать запрос с использованием JavaScript (Fetch API):
javascript
Copy code
fetch('http://api.openweathermap.org/data/2.5/weather?q=London&appid=your_api_key')
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error('Ошибка при получении данных погоды:', error));
Замените London на нужный город и your_api_key на ваш ключ API. Этот запрос вернет данные о погоде в Лондоне.

Используя подобные API, вы можете интегрировать данные о погоде в ваши веб-приложения, мобильные приложения или даже в системы Интернета вещей.

![image](https://github.com/Doonu/weather_app/assets/123429108/d7aa8895-e449-4ad2-b45e-3fac13e451a3)
