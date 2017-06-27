# TAU

TAU is Automation Framework with abilities to test Api and Ui

Тех заданияе в корне проекта в файле SPEC.pdf


<h3>Перед запуском</h3>
<p>Надеюсь читающий эти строки находитсья в хорошем расположеии духа с чашкой вкусного чая/кофе удобно сидя в креслице</p>
<p>Важны наличие JDK, GDK и Chrome/Chromium
<p>А дальше...</p>


<h3>Запуск</h3>

<ul>
 <li>
  <p>
   <strong>
    <code>./gradlew clean test</code>
   </strong>
   на Unix подобных
   </p>
  </li>
  <li>
   <p>
    <strong>
    <code>gradlew clean test</code>
    </strong>
    на Windows
   </p>
  </li>
</ul>
<p>Gradle и chromedriver выкачаются самостоятельно.</p>

<p>Если нужно запустить тесты отдельно на api или ui, то можно просто передать параметр при запуске <code>-Ptype=%sometype%</code></p>
<ul><code>./gradlew clean test -Ptype=%sometype%</code></ul>    
<p>Где параметр <strong>%sometype%</strong> может принимать значения:</p>
<ul>
 <li>
   <strong>ui</strong>
  </li>
  <li>
   <strong>api</strong> 
  </li>
</ul>

<h3>Результаты</h3>
в корне репы ./build/reports/tests/test/index.html