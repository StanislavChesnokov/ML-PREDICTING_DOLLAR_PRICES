PREDICTING DOLLAR PRICES

<strong>Цель:</strong> Прогноз курса доллар/гривна на день, неделю и месяц. Поиск сезонных закономерностей.

<strong>Задача:</strong> Прогнозирование временных рядов. Метрики качества - MAPE, MAE.

<strong>Datasets:</strong> api.privatbank.ua


<ol>
<li>Import libraries</li>
<li>Importing Data
<ul>
  <li>Import Data. Api Privatbank.</li>
  <li>Import Data. CSV file.</li>
</ul>
</li>
<li>Data analysis</li>
<li>Modeling
<ul>
  <li>Обучаем модель без параметров</li>
  <li>Добавим параметр сезонности и праздники</li>
  <li>Посчитаем ошибку модели</li>
  <li>Расчет ошибки базовой модели</li>
  <li>Расчет ошибки модели без сильной волатильности начала 2015года</li>
  <li>Расчет ошибки модели на данных 2017-2021гг.</li>
  <li>Расчет ошибки модели на данных 2019-2021гг.</li>
  <li>Прогноз на 30 дней по данным 2019-2021гг.</li>
  <li>Поиск оптимальных параметров</li>
  <li>Прогноз на 60 дней с оптимальными параметрами</li>
</ul>
</li>
</ol>

<p><h2>Курс гривна/доллар. Основные тренды и сезонные закономерности.</h2></p>

<img src="https://github.com/StanislavChesnokov/ML-PREDICTING_DOLLAR_PRICES/predict_trend.png" width="640" height="638" alt="PREDICTING DOLLAR">
