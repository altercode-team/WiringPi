## Installing


```sh
# fetch the source
sudo apt install git
git clone git@github.com:altercode-team/WiringPi.git
cd WiringPi

# build the package
./build 
```


## Uninstalling


```sh

./build uninstall

```
## Планы

Сейчас закомментированы строки с ошибками при запуске на x86_64. Когда будем настраивать кросс компиляцию, то необходимо будет раскомментировать строки. Затем настроить wiringPi.c так, чтобы при запуске на pi код отрабатывал, а при запуске на x86_64 функции становились пустышками.

