# 2-relay-Water-tank-ESPressif
/*
 * ============================================================
 *  ESP32 — 2 реле + кнопки + датчик уровня воды JSN-SR04T
 *  ESP RainMaker | ESP32 Arduino Core 2.0.17
 * ============================================================
 *  Устройства в приложении RainMaker:
 *   - Obuvnitsa  → Switch (реле 1)
 *   - Vana       → Switch (реле 2)
 *   - WaterTank  → уровень % + алерт низкого уровня
 *
 *  Пины:
 *   Реле 1    → GPIO 16
 *   Реле 2    → GPIO 17
 *   Кнопка 1  → GPIO 13
 *   Кнопка 2  → GPIO 12
 *   Wi-Fi LED → GPIO 2
 *   RESET     → GPIO 0  (3 сек = сброс Wi-Fi, 10 сек = factory reset)
 *   TRIG      → GPIO 5
 *   ECHO      → GPIO 18 (через делитель 1кОм + 2кОм!)
 *
 *  Библиотеки:
 *   - ESP RainMaker (by Espressif Systems)
 *   - AceButton (by Brian Park)
 * ============================================================
 */
