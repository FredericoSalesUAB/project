# django-skeleton
Django project skeleton

#### Application project.
---

#### System requirements.

* python3.10
* virtualenv
* virtualenvwrapper

#### Add this lines to your .profile, .zshrc or .bashrc.

    Remember to check your application path with: which [command].

```bash
export VIRTUALENVWRAPPER_PYTHON="/usr/local/bin/python"
export WORKON_HOME="$HOME/.venvs"
export PROJECT_HOME=$HOME/Documents/projects/python
export VIRTUALENVWRAPPER_SCRIPT=/opt/homebrew/bin/virtualenvwrapper.sh
source /opt/homebrew/bin/virtualenvwrapper_lazy.sh
```

---

### Generate the project sum.

    Create the new project / application.

```bash
[user@machine ~/ ] $: mkproject blog
```

    Download the project/application skeleton from the git.

```bash
(blog) [user@machine ~/Documents/projects/blog ] $: git clone https://github.com/infracead/django-skeleton.git
```



Generate the new configuration file config.json in the scripts folder.
Edit the file to reach the needed result.
    
```json
{
    "HOST"       : "localhost",
    "NAME"       : "kolmogorov",
    "USER"       : "9f0098eafbf0a44709aa8908b2d168z2xbg&(ja2)mr*-",
    "PASSWORD"   : "af4a52150834d9f0098eafbf0a44709aa8908b2d",
    "PORT"       : "5432",
    "ENGINE"     : "django.db.backends.postgresql",
    "SECRET"     : "django-insecure-jc_c$0l(s&6=a0a^5=r*168z2xbg&(ja2)mr*-fb4sn)svxsiu",
    "SITE_ID"    : "2532e07bc89da4988fbefd042d0f1f75b3c7251a",
    "TIME_ZONE"  : "America/Sao_Paulo",
    "LANGUAGE"   : "pt-BR",
    "USE_I18N"   : "True",
    "USE_TZ"     : "True",
    "STATIC_URL" : "static/",
    "ASSETS"     : "static/assets",
    "DEBUG"      : "True",
    "SQLITE"     : "blog.sqlite3"
}
```

```bash
(blog) [user@machine ~/Documents/projects/blog ] $: shasum ~/path/to/manage.py
```

#### Using the Makefile

```bash
(blog) [user@machine ~/Documents/projects/blog ] $: make help
```

---

#### Use the following skeleton.


| project   | Description        | ID_APP                                    |
|:---------:|:------------------:|:-----------------------------------------:|
| blog      | skel project CEAD  | b708bccb166e7af1a11c30101f9a328ccfa6c97a  |
| almox     | controle logistico | a11c30101f9a328ccfa6c97ab708bccb166e7af0  |
| ticket    | consumer service   | e7af1a11c30b708bccb16bccb16611c30101f9a9  |


| ID_APP                                   | ID_PROJECT |
|:----------------------------------------:|:----------:|
| b708bccb166e7af1a11c30101f9a328ccfa6c97a | A2022001   |
| b708bccb166e7af1a11c30101f9a328ccfa6c97a | A2022002   |


---