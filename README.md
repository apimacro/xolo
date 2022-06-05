# xolo.io
bot scenario based on botreck to login make a screnshoot, get a list of invoices, upload

scenarios for botreck: got xolo.io , login,get history, get domains, ..

### Add to file: apifork.txt

https://github.com/botreck/xolo xolo

```bash
echo "https://github.com/botreck/xolo xolo" >> apifork.txt
```

and install in project

```bash
./apifork install
```

start using

```bash
./apidsl 'puppeteer.csv("xolo.io/login_user_screenshot.csv")'
```