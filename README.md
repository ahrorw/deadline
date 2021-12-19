# deadline
import timer from './modules/timer'; // импорт в основный скрипт
window.addEventListener('DOMContentLoaded', () => {
let deadline = '2021-12-31'; // указание даты конечной даты
timer('.container1', deadline); // вызов скрипта с указанием контейнера таймера
}
