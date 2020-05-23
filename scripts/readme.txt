Skrypt nie jest w stanie znalezc nawet pliku, ktory lezy w jego folderze.
Próbowałem export PYTHONPATH="sciezkadoskryptu/code" oraz bez /code wg poradnika
https://bic-berkeley.github.io/psych-214-fall-2016/using_pythonpath.html

Niezależnie czy piszę od razu import czy from ... import ... wyrzuca błąd, że nie ma pierwszej lokalizacji
ze ścieżki, a więc jeżeli przykładowo w skrypcie jest:

from scripts.srv import Interpolation

to wyrzuca że nie ma scripts. Jeżeli zaś jest

from srv import Interpolation

to nie ma srv.

Jeśli edytowałby Pan ten kod w sposób, który umożliwiłby import, to dalej sobie
oczywiście poradzę. W razie użycia komendy export/edycji pliku ./bashrc to również
bym prosił o kopię.

Dziękujemy bardzo
