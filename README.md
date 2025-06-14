# Miner Empire / Шахтерская Империя

An incremental idle game where you mine resources, upgrade pickaxes, and hire miners.
(Инкрементальная idle-игра, в которой вы добываете ресурсы, улучшаете кирки и нанимаете шахтеров.)

## English

### About The Game

Miner Empire is a simple browser-based incremental idle game written in pure HTML, CSS, and JavaScript. The goal is to accumulate wealth by mining various ores, upgrading your tools, and employing miners to automate the process.

### Features

* **Clicker Mining:** Manually mine different types of ore.
* **Pickaxe Upgrades:** Improve your mining power by upgrading your current pickaxe or unlocking more powerful ones (Wood, Stone, Iron, Diamond, Netherite).
* **Miner Recruitment:** Hire various types of miners (Simple, Advanced, Expert) for a limited time to automatically extract the most valuable ore available to your current pickaxe.
* **Resource Management:** Sell your mined resources for money to fund further upgrades and recruitment.
* **Save/Load Game:** Your progress can be saved and loaded directly in the browser.
* **Basic Settings:** Adjust music and sound effects volume, and toggle background visuals.
* **Soundtrack:** Enjoy a selection of background music tracks.

### How to Play

1.  **Download** the `index.html` file and the `assets` folder.
2.  **Open** `index.html` in your web browser.
3.  **Click** on ore buttons to mine resources.
4.  **Upgrade** your pickaxe and **hire** miners using your money.
5.  **Sell** resources to earn more money.

### Console Commands (For Debugging/Cheats)

Open your browser's developer console (usually `F12` or `Ctrl+Shift+I` / `Cmd+Option+I`) and use the `debug` object:

* `debug.logState()`: Logs the current game state to the console.
* `debug.setMoney(amount)`: Sets your money to a specific amount.
* `debug.addOre(oreType, amount)`: Adds a specified amount of ore (e.g., `debug.addOre('diamond', 100)`).
* `debug.unlockPickaxe(pickaxeId)`: Unlocks a specific pickaxe (e.g., `debug.unlockPickaxe('netherite')`).
* `debug.setPickaxeLevel(pickaxeId, level)`: Sets a pickaxe's level (e.g., `debug.setPickaxeLevel('diamond', 10)`).
* `debug.addMinerContract(minerType, durationMinutes)`: Hires a miner for a duration (e.g., `debug.addMinerContract('expert', 60)`).
* `debug.resetCooldowns()`: Resets all mining cooldowns.

---

## Русский

### О Игре

"Шахтерская Империя" — это простая браузерная инкрементальная idle-игра, написанная на чистом HTML, CSS и JavaScript. Ваша цель — накапливать богатство, добывая различные руды, улучшая свои инструменты и нанимая шахтеров для автоматизации процесса.

### Возможности

* **Добыча по клику:** Вручную добывайте различные виды руды.
* **Улучшение кирок:** Повышайте свою силу добычи, улучшая текущую кирку или открывая более мощные (Деревянная, Каменная, Железная, Алмазная, Незеритовая).
* **Наем шахтеров:** Нанимайте различных шахтеров (Обычный, Опытный, Эксперт) на ограниченное время для автоматической добычи самой ценной руды, доступной вашей текущей кирке.
* **Управление ресурсами:** Продавайте добытые ресурсы за деньги, чтобы финансировать дальнейшие улучшения и наем.
* **Сохранение/Загрузка игры:** Ваш прогресс можно сохранять и загружать прямо в браузере.
* **Базовые настройки:** Регулируйте громкость музыки и звуковых эффектов, а также переключайте фоновые изображения.
* **Саундтрек:** Наслаждайтесь подборкой фоновых музыкальных треков.

### Как Играть

1.  **Скачайте** файл `index.html` и папку `assets`.
2.  **Откройте** `index.html` в вашем веб-браузере.
3.  **Нажимайте** на кнопки руды, чтобы добывать ресурсы.
4.  **Улучшайте** свою кирку и **нанимайте** шахтеров за деньги.
5.  **Продавайте** ресурсы, чтобы заработать больше денег.

### Консольные Команды (Для Отладки/Читов)

Откройте консоль разработчика вашего браузера (обычно `F12` или `Ctrl+Shift+I` / `Cmd+Option+I`) и используйте объект `debug`:

* `debug.logState()`: Выводит текущее состояние игры в консоль.
* `debug.setMoney(amount)`: Устанавливает количество ваших денег.
* `debug.addOre(oreType, amount)`: Добавляет указанное количество руды (например, `debug.addOre('diamond', 100)`).
* `debug.unlockPickaxe(pickaxeId)`: Разблокирует конкретную кирку (например, `debug.unlockPickaxe('netherite')`).
* `debug.setPickaxeLevel(pickaxeId, level)`: Устанавливает уровень кирки (например, `debug.setPickaxeLevel('diamond', 10)`).
* `debug.addMinerContract(minerType, durationMinutes)`: Нанимает шахтера на определенное время (например, `debug.addMinerContract('expert', 60)`).
* `debug.resetCooldowns()`: Сбрасывает все кулдауны на добычу.
