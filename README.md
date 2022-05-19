# Heroku Cli

<h4>Download termux!</h4>    
<p><a href="https://download.apkcombo.com/com.termux/Termux_0.118.0_apkcombo.com.apk?ecp=Y29tLnRlcm11eC8wLjExOC4wLzExOC41MThkOGEwNDliMzFlZTI4ZTBkZjczZTVmYTIxZjM4NmZjNDY4ODg4LmFwaw==&iat=1652949767&sig=0ccdc62db780ace69c4e0d363c0a6d80&size=101739523&from=cf&version=latest&lang=en&fp=a981b449f00e83d699ee4aba1f4bcbc3&ip=47.9.1.4"><img src="https://telegra.ph/file/9e955b5952bc0836a6b4b.png" alt="Press to Takeoff" width="490px"></a></p>

Enter this code in termux
```console
    ~$ apt update && apt upgrade && pkg install git && sh -c "$(curl -fsSL https://raw.githubusercontent.com/TeamScenario/Heroku-Cli-Termux-Android/TeamScenario/install.sh)" && heroku login -i
```
### After heroku login
```console
    ~$ cd /storage/emulated/0 && git clone https://github.com/TeamScenario/Scenario
```
### After clone 
```console
    ~$ cd Scenario 
```
### enter your app name instead of appname
```console
    ~$ heroku git:remote -a yourapp
```
### Final step 
```console
    ~$ git pull https://github.com/TeamScenario/Scenario && git push heroku HEAD:master
```

All done !
