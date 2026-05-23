## 1. Проверка срока действия пароля

Для пользователя `userpass` был установлен максимальный срок действия пароля — **45 дней**.

Команда:

```bash
sudo chage -M 45 userpass
```

Проверка настроек пользователя:

```bash
chage -l userpass
```

Результат проверки:

```text
Password expires: Jul 01, 2026
Maximum number of days between password change: 45
Number of days of warning before password expires: 7
```

Это подтверждает, что пароль пользователя `userpass` истекает через 45 дней.

![Проверка срока действия пароля](images/01_password_expiration_check.png)
