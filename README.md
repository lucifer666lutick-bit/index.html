<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<style>
body {
  margin: 0;
  background: transparent;
  overflow: hidden;
  height: 100vh;
}
#ticker {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: 60px;
  font-weight: 900;
  font-family: 'Arial Black', sans-serif;
  position: absolute;
  top: 100%;
  animation: scrollDown 20s linear infinite;
}
@keyframes scrollDown {
  0% { top: -100%; }
  100% { top: 100%; }
}
.line {
  margin: 20px 0;
  text-shadow: 2px 2px 10px;
}
.cartoon { color: #ff69b4; text-shadow: 2px 2px 10px #ff69b4, 0 0 20px #ff69b4, 0 0 30px #ff69b4; }
.horror { color: #ff0000; text-shadow: 2px 2px 10px #ff0000, 0 0 20px #ff0000, 0 0 30px #ff0000; }
.romance { color: #00ffff; text-shadow: 2px 2px 10px #00ffff, 0 0 20px #00ffff, 0 0 30px #00ffff; }
</style>
</head>
<body>
<div id="ticker">
  <div class="line cartoon">🟣 Шрек</div>
  <div class="line cartoon">🟣 Рапунцель</div>
  <div class="line cartoon">🟣 Холодное сердце</div>
  <div class="line horror">🔴 Заклятие</div>
  <div class="line horror">🔴 Оно</div>
  <div class="line horror">🔴 Астрал</div>
  <div class="line romance">💙 Дневник памяти</div>
  <div class="line romance">💙 Ла-Ла Ленд</div>
  <div class="line romance">💙 До встречи с тобой</div>
  <div class="line romance">💙 Виноваты звёзды</div>
</div>
</body>
</html>
