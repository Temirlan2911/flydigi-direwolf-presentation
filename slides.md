---
theme: default
title: FLYDIGI Direwolf
info: Рекламная презентация игрового контроллера
class: text-white
aspectRatio: 16/9
transition: slide-left
mdc: true
fonts:
  sans: Inter
  mono: JetBrains Mono
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&family=JetBrains+Mono:wght@500;700&display=swap');

:root {
  --blue: #39a7ff;
  --cyan: #8be8ff;
  --ink: #08111f;
  --muted: #9fb3c8;
}

.slidev-layout {
  background:
    radial-gradient(circle at 80% 10%, rgba(57,167,255,.22), transparent 30%),
    radial-gradient(circle at 10% 85%, rgba(88,52,180,.2), transparent 35%),
    #08111f;
}

.headline {
  font-size: 4.7rem;
  line-height: .96;
  letter-spacing: -.06em;
  font-weight: 800;
}

.eyebrow {
  color: var(--cyan);
  font-family: 'JetBrains Mono', monospace;
  letter-spacing: .12em;
  text-transform: uppercase;
  font-size: .82rem;
}

.muted { color: var(--muted); }
.blue { color: var(--blue); }

.glass {
  background: linear-gradient(135deg, rgba(255,255,255,.1), rgba(255,255,255,.03));
  border: 1px solid rgba(255,255,255,.14);
  border-radius: 24px;
  backdrop-filter: blur(12px);
}

.feature {
  padding: 1.15rem 1.25rem;
  min-height: 150px;
}

.feature h3 { margin: 0 0 .45rem; color: white; }
.feature p { margin: 0; color: var(--muted); font-size: .94rem; line-height: 1.4; }

.controller {
  filter: drop-shadow(0 28px 30px rgba(0,0,0,.4));
  animation: float 5s ease-in-out infinite;
}

.pulse {
  animation: pulse 2.2s ease-in-out infinite;
}

@keyframes float {
  0%, 100% { transform: translateY(0) rotate(-2deg); }
  50% { transform: translateY(-14px) rotate(2deg); }
}
@keyframes pulse {
  0%, 100% { opacity: .35; transform: scale(.96); }
  50% { opacity: .8; transform: scale(1.04); }
}

.tag {
  display: inline-block;
  border: 1px solid rgba(139,232,255,.35);
  color: var(--cyan);
  border-radius: 999px;
  padding: .35rem .7rem;
  font-size: .78rem;
  margin-right: .4rem;
}

.quote {
  border-left: 3px solid var(--blue);
  padding-left: 1.25rem;
  font-size: 1.5rem;
  line-height: 1.3;
}
</style>

<!--
Speaker split:
  Speaker 1: slides 1–5, about 4 minutes.
  Speaker 2: slides 6–10, about 4 minutes.
-->

# FLYDIGI **Direwolf**

<div class="eyebrow mt-6">CONTROL THE MOMENT</div>

<div class="grid grid-cols-2 gap-10 items-center mt-8">
<div>
  <div class="headline">Игра начинается<br><span class="blue">с ощущения.</span></div>
  <p class="text-xl muted mt-7 max-w-xl">Универсальный контроллер для тех, кто хочет играть точнее, дольше и без лишних ограничений.</p>
  <div class="mt-8"><span class="tag">PC</span><span class="tag">Mobile</span><span class="tag">Nintendo Switch</span></div>
</div>
<div class="flex justify-center">
  <img class="controller w-120" src="./public/controller-front.svg">
</div>
</div>

<!--
SPEAKER 1 — 35 sec
Сегодня мы представляем FLYDIGI Direwolf — контроллер, который превращает обычную игру в более точный и комфортный опыт. Мы покажем, почему это не просто аксессуар, а удобный инструмент для разных платформ и жанров.
-->

---

# Знакомая форма. **Другой уровень контроля.**

<div class="grid grid-cols-3 gap-5 mt-12">
<div class="glass feature" v-click>
  <div class="text-4xl mb-5">⌁</div>
  <h3>Эргономика</h3>
  <p>Симметричная форма и текстурированные рукоятки помогают играть дольше без лишнего напряжения.</p>
</div>
<div class="glass feature" v-click>
  <div class="text-4xl mb-5 blue">◉</div>
  <h3>Точность</h3>
  <p>Два аналоговых стика и полноценная крестовина дают контроль и в шутерах, и в гонках, и в файтингах.</p>
</div>
<div class="glass feature" v-click>
  <div class="text-4xl mb-5">↯</div>
  <h3>Свобода</h3>
  <p>Проводное и беспроводное подключение — выбирайте стабильность или мобильность под задачу.</p>
</div>
</div>

<div class="absolute bottom-8 right-10 muted text-sm">01 / WHY IT MATTERS</div>

<!--
SPEAKER 1 — 45 sec
Главная проблема обычного управления — компромисс. Клавиатура даёт много кнопок, но не всегда комфортна. Сенсорный экран удобен, но ему не хватает тактильной точности. Direwolf занимает середину: привычная раскладка, физические кнопки и удобный хват.
-->

---

# Один контроллер — **несколько игровых миров**

<div class="grid grid-cols-2 gap-12 items-center mt-8">
<div>
  <div class="flex items-center gap-4 mb-8" v-click>
    <div class="text-3xl blue">01</div><div><b>PC</b><div class="muted">низкая задержка через адаптер или кабель</div></div>
  </div>
  <div class="flex items-center gap-4 mb-8" v-click>
    <div class="text-3xl blue">02</div><div><b>Телефон / планшет</b><div class="muted">Bluetooth для игр в дороге</div></div>
  </div>
  <div class="flex items-center gap-4" v-click>
    <div class="text-3xl blue">03</div><div><b>Nintendo Switch</b><div class="muted">отдельный режим подключения</div></div>
  </div>
</div>
<div class="glass p-7">
  <div class="eyebrow mb-4">ONE DEVICE / MANY PLATFORMS</div>
  <div class="text-4xl font-bold leading-tight">Не покупайте<br><span class="blue">три разных</span><br>контроллера.</div>
  <div class="muted mt-6">Переключайтесь между сценариями, а не между аксессуарами.</div>
</div>
</div>

<!--
SPEAKER 1 — 50 sec
Direwolf полезен не только дома за компьютером. По данным инструкции линейки Direwolf, предусмотрены режимы для PC, Android, iOS и Switch. Это особенно удобно для тех, кто играет на нескольких устройствах и не хочет каждый раз привыкать к новой раскладке.
-->

---

# Детали, которые чувствуются **в игре**

<div class="grid grid-cols-2 gap-6 mt-8">
<div class="glass p-7" v-click>
  <div class="eyebrow">01 / STICKS</div>
  <h2 class="text-2xl font-bold mt-3">Два стика с текстурой</h2>
  <p class="muted mt-3">Синий акцент помогает быстро ориентироваться, а рельефная поверхность не даёт пальцу соскользнуть в напряжённый момент.</p>
</div>
<div class="glass p-7" v-click>
  <div class="eyebrow">02 / D-PAD</div>
  <h2 class="text-2xl font-bold mt-3">Гибридная крестовина</h2>
  <p class="muted mt-3">Подходит для диагональных движений, меню, платформеров и точных комбинаций.</p>
</div>
<div class="glass p-7" v-click>
  <div class="eyebrow">03 / TRIGGERS</div>
  <h2 class="text-2xl font-bold mt-3">Большие плечевые кнопки</h2>
  <p class="muted mt-3">Указательные пальцы остаются на управлении, а остальные кнопки доступны без смены хвата.</p>
</div>
<div class="glass p-7" v-click>
  <div class="eyebrow">04 / USB-C</div>
  <h2 class="text-2xl font-bold mt-3">Современная зарядка</h2>
  <p class="muted mt-3">Один распространённый кабель — для зарядки и проводной игры.</p>
</div>
</div>

<!--
SPEAKER 1 — 55 sec
Реклама работает не только через список характеристик. Важно, что человек ощущает руками. Здесь есть текстурированные стики, крупные плечевые кнопки, гибридная крестовина и USB-C. Это детали, которые заметны уже в первой игре.
-->

---

# **M1 / M2** — преимущество, которое остаётся за спиной

<div class="grid grid-cols-2 gap-12 items-center mt-8">
<div class="relative">
  <div class="pulse absolute w-72 h-72 rounded-full bg-blue-400/30 blur-3xl left-15 top-5"></div>
  <img class="relative w-115" src="./public/controller-back.svg">
</div>
<div>
  <div class="eyebrow">BACK CONTROL</div>
  <div class="quote mt-5">Побеждает не тот, кто нажимает больше. А тот, кто тратит меньше времени на лишние движения.</div>
  <div class="mt-8 space-y-4">
    <div v-click><b>Шутеры:</b> прыжок или приседание без отпускания стика.</div>
    <div v-click><b>Гонки:</b> быстрый доступ к дополнительной функции.</div>
    <div v-click><b>Игры с комбинациями:</b> назначьте действие под себя.</div>
  </div>
</div>
</div>

<!--
SPEAKER 1 — 55 sec
Ключевая рекламная фишка — две кнопки на задней стороне. Их можно использовать для часто повторяющихся действий. В шутере это может быть прыжок, в гонке — дополнительная функция, а в любой игре — команда, до которой обычно приходится тянуться большим пальцем. На этом заканчивается первая часть: форма, совместимость и контроль.
-->

---

# Не просто контроллер. **Игровой апгрейд.**

<div class="grid grid-cols-2 gap-10 items-center mt-10">
<div>
  <div class="eyebrow">PART 2 / THE EXPERIENCE</div>
  <div class="headline mt-5">Почувствуйте<br><span class="blue">разницу.</span></div>
  <p class="text-xl muted mt-7">Теперь посмотрим, как Direwolf превращает функции в реальные преимущества.</p>
</div>
<div class="glass p-8">
  <div class="text-5xl font-bold blue">4:00</div>
  <div class="text-xl mt-3">минуты до финального выбора</div>
  <div class="muted mt-4">Комфорт · скорость · универсальность</div>
</div>
</div>

<!--
SPEAKER 2 — 25 sec
До этого мы говорили о том, что находится внутри и снаружи контроллера. Теперь — о результате для пользователя: как он ощущается в реальной игре и почему за него стоит заплатить.
-->

---

# Три сценария, где Direwolf раскрывается

<div class="grid grid-cols-3 gap-5 mt-12">
<div class="glass p-7" v-click>
  <div class="text-5xl mb-6">⚡</div>
  <div class="eyebrow">ACTION</div>
  <h2 class="text-2xl font-bold mt-3">Шутеры</h2>
  <p class="muted mt-4">Стик отвечает за движение и камеру, триггеры — за точное действие, M1/M2 — за команды без потери контроля.</p>
</div>
<div class="glass p-7" v-click>
  <div class="text-5xl mb-6">◒</div>
  <div class="eyebrow">RACING</div>
  <h2 class="text-2xl font-bold mt-3">Гонки</h2>
  <p class="muted mt-4">Плавное управление стиками и удобные триггеры дают более естественное ощущение газа, тормоза и поворота.</p>
</div>
<div class="glass p-7" v-click>
  <div class="text-5xl mb-6">✦</div>
  <div class="eyebrow">CASUAL</div>
  <h2 class="text-2xl font-bold mt-3">Игры с друзьями</h2>
  <p class="muted mt-4">Подключили — и играете. Подходит для быстрых матчей, платформеров и совместного отдыха.</p>
</div>
</div>

<!--
SPEAKER 2 — 50 sec
У Direwolf есть три сильных сценария. В экшен-играх важны быстрые реакции и задние кнопки. В гонках — плавность стиков и триггеров. В играх с друзьями — простое подключение и привычная раскладка. Один продукт закрывает разные потребности.
-->

---

# Настройте управление **под себя**

<div class="grid grid-cols-2 gap-10 items-center mt-9">
<div class="glass p-8">
  <div class="eyebrow">FLYDIGI SPACE STATION</div>
  <div class="text-3xl font-bold mt-4">Контроллер не диктует стиль игры.</div>
  <div class="mt-7 space-y-4">
    <div v-click><span class="blue">→</span> переназначьте кнопки</div>
    <div v-click><span class="blue">→</span> настройте дополнительные команды</div>
    <div v-click><span class="blue">→</span> сохраните удобный профиль</div>
  </div>
</div>
<div>
  <div class="font-mono text-sm text-cyan-200/80 mb-3">YOUR_PROFILE.json</div>
  <div class="rounded-2xl bg-black/40 border border-white/10 p-6 font-mono text-sm leading-7">
    <span class="text-pink-300">{</span><br>
    &nbsp;&nbsp;<span class="text-cyan-200">"mode"</span>: <span class="text-green-300">"competitive"</span>,<br>
    &nbsp;&nbsp;<span class="text-cyan-200">"back_left"</span>: <span class="text-green-300">"jump"</span>,<br>
    &nbsp;&nbsp;<span class="text-cyan-200">"back_right"</span>: <span class="text-green-300">"crouch"</span>,<br>
    &nbsp;&nbsp;<span class="text-cyan-200">"platform"</span>: <span class="text-green-300">"PC"</span><br>
    <span class="text-pink-300">}</span>
  </div>
</div>
</div>

<!--
SPEAKER 2 — 55 sec
Ещё одно преимущество — настройка через Flydigi Space Station. Можно переназначать кнопки и сохранять собственный профиль. Поэтому один и тот же контроллер может быть настроен для соревновательной игры, гонок или просто удобного управления.
-->

---

# Честный выбор: что важно знать

<div class="grid grid-cols-2 gap-6 mt-10">
<div class="glass p-8 border-green-300/20" v-click>
  <div class="text-green-300 text-xl font-bold">Сильные стороны</div>
  <div class="mt-5 space-y-3 muted">
    <div>✓ удобная симметричная форма</div>
    <div>✓ несколько способов подключения</div>
    <div>✓ две задние переназначаемые кнопки</div>
    <div>✓ USB-C и поддержка нескольких платформ</div>
  </div>
</div>
<div class="glass p-8 border-yellow-300/20" v-click>
  <div class="text-yellow-200 text-xl font-bold">Перед покупкой</div>
  <div class="mt-5 space-y-3 muted">
    <div>! точная ревизия зависит от модели</div>
    <div>! часть функций требует приложения</div>
    <div>! совместимость лучше проверить под свою игру</div>
    <div>! это не замена профессиональному симулятору</div>
  </div>
</div>
</div>

<!--
SPEAKER 2 — 50 sec
Хорошая реклама должна быть честной. Direwolf силён универсальностью, задними кнопками и удобством. Но точные функции зависят от ревизии, поэтому перед покупкой стоит проверить модель и совместимость с конкретной игрой. Для обычного PC и кроссплатформенной игры это разумный апгрейд.
-->

---

# Наш вердикт

<div class="grid grid-cols-2 gap-12 items-center mt-8">
<div>
  <div class="eyebrow">FINAL SCORE</div>
  <div class="headline mt-5"><span class="blue">Играй.</span><br>Настраивай.<br>Побеждай.</div>
  <p class="text-xl muted mt-7">FLYDIGI Direwolf — выбор для игрока, которому нужен комфорт консоли и гибкость современного устройства.</p>
</div>
<div class="glass p-8">
  <div class="text-6xl font-bold blue">4.5<span class="text-3xl text-white">/5</span></div>
  <div class="mt-7 space-y-4">
    <div class="flex justify-between"><span>Комфорт</span><span class="blue">★★★★★</span></div>
    <div class="flex justify-between"><span>Универсальность</span><span class="blue">★★★★★</span></div>
    <div class="flex justify-between"><span>Настройка</span><span class="blue">★★★★☆</span></div>
    <div class="flex justify-between"><span>Цена / возможности</span><span class="blue">★★★★★</span></div>
  </div>
</div>
</div>

<!--
SPEAKER 2 — 55 sec
Наш итог: Direwolf — это не обещание выиграть за вас. Это инструмент, который убирает лишние движения, даёт удобный хват и работает в разных игровых сценариях. Если нужен один белый универсальный контроллер для PC, мобильных устройств и Switch, это сильный кандидат.
-->

---

# Спасибо за внимание

<div class="flex items-center justify-between mt-16">
<div>
  <div class="eyebrow">QUESTIONS?</div>
  <div class="text-5xl font-bold mt-5">Попробуйте<br><span class="blue">сами.</span></div>
  <p class="muted mt-6">Лучший способ оценить контроллер — взять его в руки и сыграть один раунд.</p>
</div>
<img class="controller w-100" src="./public/controller-front.svg">
</div>

<div class="absolute bottom-7 left-10 text-xs muted">
  Источники: flydigi.com · руководство Direwolf · visual identification by provided photos
</div>

<!--
SPEAKER 2 — 40 sec
Спасибо за внимание. Мы готовы показать контроллер вживую и ответить на вопросы.
-->
