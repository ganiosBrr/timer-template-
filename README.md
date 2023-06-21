# timer-template-
Timer template that start function setClock() which initialize all selectors that we need and starts function updateClock() every second.
UpdateClock() starts getTimeRemaining function which calculates and return object with remaining time.
If total time is less than 0 we clear our interval and stop updateClock.