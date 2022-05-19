
# Vixie Cron

*The **Cron** Flavor That Runs On Most Systems.*

<br>

<div align = center>

---

[![Button Configure]][Configure]  
[![Button Changes]][Changes]  
[![Button Mails]][Mails]  
[![Button Thanks]][Thanks]

---
  
<br>

This version of **Cron** is functionally based on <br>
**System V**s implementation and thus allows <br>
every user to have their own **CronTab** file.

</div>

<br>



<br>

### Tabs

All crontab files are stored in a <br>
read-protected folder, usually <br>
in `/var/cron/tabs` .

<br>

### At

**No direct support is provided for `at` .**

However you can still use `atrun` <br>
from your **CronTab** as usual.

⤷ If your system doesn't support `atrun` , <br>
such as **System V**, you will have problem.

<br>

### Logging

Every time a command is run, <br>
a message will be logged.

<br>

### Access

You can control access to the `crontab` <br>
command by utilizing the `allow` and <br>
`deny` files in `/var/cron` .

*The command is used to install crontabs.*

<br>

### System V

While it hasn't been tested yet, some effort <br>
has gone into making porting to it easier.


<!----------------------------------------------------------------------------->

[Configure]: Documentation/Configure.md
[Changes]: Documentation/Changelog.md
[Thanks]: Documentation/Thanks.md
[Mails]: Documentation/Mail.md


<!-------------------------------{ Buttons }----------------------------------->

[Button Configure]: https://img.shields.io/badge/Configure-179287?style=for-the-badge&logo=WindowsTerminal&logoColor=white
[Button Changes]: https://img.shields.io/badge/Changelog-2478b5?style=for-the-badge&logo=Git&logoColor=white
[Button Thanks]: https://img.shields.io/badge/Thanks-d74078?style=for-the-badge&logo=GitHubSponsors&logoColor=white
[Button Mails]: https://img.shields.io/badge/Mails-yellow?style=for-the-badge&logo=GMail&logoColor=white


