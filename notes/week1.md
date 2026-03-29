Week 1 - Git basics ahd n8n introduction
Day 2 - created repo structure, learned git add, commit, push
gitignore - eto spisok faylov kotorye Git ne otpravlyaet na GitHub (paroli, sekrety)

## Week 1 - Final



### Chto sdelal

* Ustanovil Git, sozdal repozitorij na GitHub
* Ustanovil Docker, sozdal postojannyi kontejner s n8n
* Sozdal workflow week1-basic-http: Schedule Trigger → HTTP Request → IF → Edit Fields
* Sozdan workflow week1-error-handler: Error Trigger → Edit Fields → Telegram
* Podkljuchil Telegram bota dlja uvedomlenij ob oshibkah



### Chto uznal

* .gitignore - eto spisok fajlov kotorye Git ne otpravljaet na GitHub (paroli, sekrety, .env)
* Error Triger rabotaet tolko v production, ne v rejime testa
* Schedule Trigger nujen chtoby workflow zapuskalsja avtomaticheski i Error Trigger mog lovit oshibki
* .gitkeep - pustoj fajl chtoby Git videl pustuju papku



### Komandy Git

* git init, git add, git commit -m, git push, git status, git log --oneline



\### Workflows

* week1-basic-http - delaet GET zapros, proverjaet est' li pole title v otvete
* week1-error-handler - lovit oshibki iz drugih workflow i otpravljaet uvedomlenija v Telegram

