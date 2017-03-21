<h2> Битва средиземья</h2>
<h3>Суть данного алгоритма заключается в следующем:</h3>
<ul>
  <li>Есть цивилизация MiddleEarthCitizen</li>
  <li>В цивилизации есть жители </li>
  <li>Жители делятся на светлых и темных</li>
  <li>У каждого есть определенный уровень силы</li>
  <li>Светлые и темные делятся на всадников и пехоту</li>
  <li>Необходимо создать и произвольным образом заполнить 2 армии</li>
  <li>Провести бой</li>
  <li>Определить победителя</li>
</ul>
<h3>Правила проведения боя</h3>
<h4>Первый раунд</h4>
<ul>
  <li>Сражаются только всадники</li>
  <li>Перед сражением произвольным образом определяется, кто из воинов наносит первый удар</li>
  <li>При нанесении удара противник теряет силу на уровень силы атакующего воина</li>
  <li>Если противник остался жив, он наносит ответный удар по аналогичному принципу</li>
  <li>Противник погибает, если сила удара больше оставшейся силы</li>
  <li>После завершения сражения 1-1, очередь переходит к следующей паре воинов</li>
  <li>Если в какой-то из армий очередь дошла до последнего воина, то в сражение втсупает первый воин из этой армии (цикл)</li>
</ul>
<h4>Второй раунд</h4>
<ul>
  <li>Сражается пехота</li>
  <li>Второй раунд проходит по тому же принципу</li>
  <li>Если по окончании второго раунда в обоих раундах остались воины проходит третий раунд</li>
  <li></li>
</ul>
<h4>Третий раунд</h4>
<ul>
    <li>Сражаются и всадники и пешие</li>
    <li></li>
    <li>Побеждает та армия, в которой остался хотя бы 1 воин.</li>
</ul>

<h4>Дополнительная информация</h4>
  <h5>Светлая армия:</h5> 
    <h6>Всадники:</h6>
      <ul>
        <li>Wizard(20 + horse power(4-5))</li>
        <li>Rohhirim(Human power + horse power)</li>
      </ul>
    <h6>Пехота:</h6>
      <ul>
         <li>WoodenElf(6)</li>
         <li>Human(7-8)</li>
         <li>Elf(4-7)</li>
      </ul>
  
  <h5>Темная армия:</h5> 
    <h6>Всадники:</h6>
      <ul>
        <li>Orc(8-10 + wolf power(4-7))</li>
      </ul>
    <h6>Пехота:</h6>
    <ul>
       <li>Goblin(2-5)</li>
       <li>UrukHai(10-12)</li>
       <li>Troll(11-15)</li>
    </ul>
