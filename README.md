<div id="current_date_time_block"></div>

<script type="text/javascript">
    
    /* функция добавления ведущих нулей */
    /* (если число меньше десяти, перед числом добавляем ноль) */
    function zero_first_format(value)
    {
        if (value < 10)
        {
            value='0'+value;
        }
        return value;
    }

    /* функция получения текущей даты и времени */
    function date_time()
    {
        var current_datetime = new Date();
        var day = zero_first_format(current_datetime.getDate());
        var month = zero_first_format(current_datetime.getMonth()+1);
        var year = current_datetime.getFullYear();
        var hours = zero_first_format(current_datetime.getHours());
        var minutes = zero_first_format(current_datetime.getMinutes());
        var seconds = zero_first_format(current_datetime.getSeconds());

        return day+"."+month+"."+year+" "+hours+":"+minutes+":"+seconds;
    }

    /* выводим текущую дату и время на сайт в блок с id "current_date_time_block" */
    document.getElementById('current_date_time_block').innerHTML = date_time();
</script>
<h1 align="center"> <span style="border:2px HotPink; padding:3px;"> <span style="color:GoldenRod;"> Владислав Соловьев </span> </span> </h1> 

<h3 align="center"> <i> "Кто ВЛАДеет информацией - тот ВЛАДеет миром" </i> </h3>

<h4 align="right"> <i> Натан Ротшильд </i> </h4> 
<br> <br>
<strong> <a href = "https://disk.yandex.ru/i/Wen4dDEMOEzmKw">  <span style="color:ForestGreen; text-decoration: underline;"> Основы программирования и баз данных </span> </a> </strong>


<strong> <a href = "https://disk.yandex.ru/i/DQEwELw0Qi2n-g">  <span style="color:ForestGreen; text-decoration: underline;"> Основы SQL и Баз Данных </span> </a> </strong>


<strong> <a href = "https://disk.yandex.ru/i/J49aBAkxaAym0Q">  <span style="color:ForestGreen; text-decoration: underline;"> "Поколение Python": курс для начинающих </span> </a> </strong>


<strong> <a href = "https://disk.yandex.ru/i/CW3_LqOFD1AmbQ">  <span style="color:ForestGreen; text-decoration: underline;"> Excel: простые шаги для оптимизации работы с данными </span> </a> </strong>


<strong> <a href = "https://disk.yandex.ru/i/VjWQE7qnmvLFeA">  <span style="color:ForestGreen; text-decoration: underline;"> Junior data analyst: младший аналитик данных  </span> </a> </strong>


<strong> <a href = "https://disk.yandex.ru/i/ynKe8XpvQKo72A">  <span style="color:ForestGreen; text-decoration: underline;"> Pandas  </span> </a> </strong>


<strong> <a href = "https://disk.yandex.ru/i/SoXgYrq4UnRQ1Q">  <span style="color:ForestGreen; text-decoration: underline;"> Data Visualization  </span> </a> </strong>


<strong> <a href = "https://disk.yandex.ru/i/cqq1AEX22PX-Ng">  <span style="color:ForestGreen; text-decoration: underline;"> Intro to AI Ethics  </span> </a> </strong>


<strong> <a href = "https://disk.yandex.ru/i/SMWaJgkVbwRyeQ">  <span style="color:ForestGreen; text-decoration: underline;"> Intro to Machine Learning  </span> </a> </strong>


<strong> <a href = "https://disk.yandex.ru/i/xLbceRalz0wpmg">   <span style="color:ForestGreen; text-decoration: underline;"> Wildberries Day  </span> </a> </strong>

<strong> <a href = "https://disk.yandex.ru/i/znHkkbgVpn0wxg">   <span style="color:ForestGreen; text-decoration: underline;"> Управление высокотехнологичными проектами </span> </a> </strong>

<strong> <a href = "https://disk.yandex.ru/i/os9Cbr0qpaP7FA">   <span style="color:ForestGreen; text-decoration: underline;"> Introduction to Agile Development and Scrum </span> </a> </strong>
