# Tablonix

HTML table based clone of *Xonix*.  All in a single file (with the exception of jQuery, taken via cdn).

Accept some game configuration via query params:
* `level`: game level (higher level contains more enemies and have less time to be completed; defaults to 1);
* `speed`: movement speed in milliseconds (default is 100);
* `objective`: percentage of coverage needed to complete a level (default is 75);
* `w`: width of the board (default is 100; board doesn't scroll, so this is probably the best width you could use);
* `h`: height of the board (default is 100; board doesn't scroll, so this is probably the best height you could use).

There are also:
* `previous_score`: last level score is passed through query param;
* `xn`: number of lives.

Those are passed via query param from level to level, so you can cheat; I don't care.