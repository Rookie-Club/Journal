Bienvenue sur le journal du Rookie club. C'est une formation en alternance pour accompagner les développeurs junior dans leurs premiers pas en entreprise.

Cette formation se déroule en alternance, ce journal ne concerne que les moments de cours.

Les cours sont assurés par [ut7](http://ut7.fr).

Si vous voulez :
- participer en tant qu'apprenant/e
- recruter un/e développeur/se formé au bonne pratique
- juste en savoir plus

envoyez nous en message [training@ut7.fr](mailto:training@ut7.fr).

## Les prérequis

- Un ordinateur portable.
- Un terminal unix (pour windows, installer [cygwin](https://www.cygwin.com/) par exemple).
- [Tmux](https://tmux.github.io/) installé dessus.
- Une clef [SSH](http://fr.wikipedia.org/wiki/OpenSSH) publique.
- [Git](https://git-scm.com/) installé.
- S'assurer que [Vi(m)](http://www.vim.org/) est installé sur la machine.
- Installer [Docker](https://www.docker.com/).
- Un compte [github](https://github.com), en attendant autre chose.

## Les derniers jours

* [[Vendredi 26 août 2016|20160826-jour33]]
* [[Vendredi 19 août 2016|20160819-jour32]]
* [[Vendredi 12 août 2016|20160812-jour31]]
* [[Vendredi 5 août 2016|20160805-jour30]]
* [[Vendredi 29 juillet 2016|20160729-jour29]]
* [[Vendredi 22 juillet 2016|20160722-jour28]]
* [[Vendredi 8 juillet 2016|20160708-2-rookies]]
* [[Vendredi 1er juillet 2016|20160701-3-rookies]]
* [[Vendredi 24 juin 2016|20160624-3-rookies-et-un-stagiaire]]
* [[Vendredi 17 juin 2016|20160617-3-rookies]]
* [[Vendredi 10 juin 2016|20160610-jour23]]
* [[Vendredi 3 juin 2016|20160603-jour22]]
* [[Vendredi 27 mai 2016|20160527-jour21]]
* [[Vendredi 20 mai 2016|20160520-jour20]]
* [[Vendredi 13 mai 2016|20160513-jour19]]
* Vendredi 29 avril 2016 jour18 .. _404_
* [[Vendredi 22 avril 2016|20160422-jour17]]
* [[Vendredi 15 avril 2016|20160415-jour16]]
* [[Vendredi 8 avril 2016|20160408-jour15]]
* [[Mercredi 23 mars 2016|20160323-jour14]]
* [[Mardi 22 mars 2016|20160322-jour13]]
* [[Lundi 21 mars 2016|20160321-jour12]]
* [[Mercredi 9 mars 2016|20160309-jour11]]
* [[Mardi 8 mars 2016|20160308-jour10]]
* [[Lundi 7 mars 2016|20160307-jour9]]
* [[Mercredi 17 février 2016|20160217-jour8]]
* [[Mardi 16 février 2016|20160216-jour7]]
* [[Lundi 15 février 2016|20160215-jour6]]
* [[Mercredi 3 février 2016|20160203-jour5]]
* [[Mardi 2 février 2016|20160202-jour4]]
* [[Lundi 1 février 2016|20160201-jour3]]
* [[Mardi 19 janvier 2016|20160119-jour2]]
* [[Lundi 18 janvier 2016|20160118-jour1]]


## Les trucs pour partager une session tmux

<pre>
command="/usr/bin/tmux -L rookieclub attach",no-port-forwarding,no-X11-forwarding,no-agent-forwarding ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDa8kidBDEzDlGuRWCQ6BKV5/8qhayXqqrVaaXnt4sxM7R3+C6qSsfUpzktGrpGdUDdKKOmLGLgwcekhSsguNva1PHUAEyY07R1Qbbb8JAkxjL2mJfJh1apJz6oL/0i8Wb933Fdxe5s0lceh+VDZnGX7idaADLlsTlLdFnXlC/4s7WE2pegkD5rtPfNGMvrSp6ofIHky2TddbYQWLoXU94QkSxRGYok6epl9VGJbGFWNg3NWSPbpOx8MnJv7WX7uOzfpkpT0p+Y63KnSQOv/ES0qwAzEubIwQs8EU44itzWkWeW1SRrJkPKY/tS4rVtNofVXTFZoBToKGqDU3AlIGMd sims38930@gmail.com
command="/usr/bin/tmux -L rookieclub attach",no-port-forwarding,no-X11-forwarding,no-agent-forwarding ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQCkHyeNR9QwToyNyA9oCN/nqvMeI0Q/riAaRURwfgFGQfEGxJ5ybbXOfloXITG6ohAWaoWJN3jL7uP3p51ecUM34hV74tH69wenCD/4/FZEFZszy1sAVt27smuSL/gF1tFDf3rfHHhPitn1i/gwG8uQVH8/4a8gD6HbWlZUkbxDZVN/xeVuwngqSaw0rubFplSWPOWylIFha7TcQk2UAgCBLr2S2unWchh5wuZFJqdZwL154bODF/Ea/+2toryfRBZXYEM3OYTGNI5HF8xOlKtNwv2R0ZXGSv5UiPt69jfthtmmaZ7BozlHxhkOFA2IyOWiLOWBM45lNapZNsXZ7/jX bosco.yohann@gmail.com
command="/usr/bin/tmux -L rookieclub attach",no-port-forwarding,no-X11-forwarding,no-agent-forwarding ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDfQXcBQLRvNJ2V3V6gzrWO25iBHeX2M3+vj8LSRwpZgrzWjSEEgJPfswmzg9lAuv2uXuFS+Ju2eW6v77c359g4mnQVhWmQIazKMWU5jtgwXO5FNCzWiGYZ5A9lvRKkbVdjze8GS30vdX0xCyL9bBylbBU9W8+YzSJiV3Lomzb54xMNsl9okMJID5KEDD1aB6ejZtYUTb+5Op1lJfyDJe75HZJfmSv5XRaczqsZM6b37EgthRdTgTvbuhr5BInWCVleKRkzdJEBNJPasjYYV5Lrl1e8chuvvwBP0InBDxfRqufvoCuZ6fVzldxuSV5mBR8zmbQg2P4NuLDBVC65V3gp hafid.traikzi@gmail.com
command="/usr/bin/tmux -L rookieclub attach",no-port-forwarding,no-X11-forwarding,no-agent-forwarding ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDRQ+Hrv/Y/E9z7d73n11h8IuBuKSrMFT6UEgJOppntMY1F02qai82PPt+4Mlj8jA6KH5lT8IhKC+IPmstG2EVraHBP0o5lzzlMV+B1+GjUKcRgQHe/bea7fHwG2o9t2HMet6Y2golilAane5QKOZG9nLgkGHX8NYbVfynTnMKupZXuiGZb+SiS+FzQZkebll+Ll0Mr2YKq2Uhw+t6sfCCe7khSLgTtSNShTBs/M++hthUyR3fNmauRKLwwolu7j4weLLWvVG2x/17iETmaqj3J3a5rTwblnziqZ6TjWtotsG3wRNeDftSbPGBhxCM3qg9mMYET4wJ+4YnOadhEjXyx semia.ladjal@gmail.com
command="/usr/bin/tmux -L rookieclub attach",no-port-forwarding,no-X11-forwarding,no-agent-forwarding ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDDWA7UHaLHR+JjDBFz3UmxaoSc+BUQu98wIIbUXCmbNrniO+WAtdQcXPuSjy/jb7/X08az0pwGyoGOsFXemiiDrtCmc5SE/2ArUZDM0FxSUGXt6OxX2R5sod4Gt8wtuHrPp1oBysI3tjuvLucvIkYZUsfzH/rUNvLTlNvrhv0TeAHg0pijbGOnM9POS7HMJzzJYPKyWakKlhpfycZL/E2z3zpGA/gR2uOolQGV61d9/kEHJNkTaHgianTV+qkdmdmgu25eH54aK7Wa7pWwfrd/yQo3Afu9D6mrlPytcTe7Iss4WIlv+gHJnhog/mX3dl20l6MH0C/YuBdib27JjWPp yannick@ut7.fr
command="/usr/bin/tmux -L rookieclub attach",no-port-forwarding,no-X11-forwarding,no-agent-forwarding ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDWGiEKhDQ5QFxyJW2eLLT2s5bY9nlXabtfY2pYocZT7cwmHws2pHBJh94HEhQ+ZSCBYb5KzgbMXDwL/IA1kHPXSt/+gT8LCQeoIOLWTw+QHlu2Ee7EL7estXv3kRlU5YWxLXlogkBXp8bE+z/Eukl7ivncY+KWakM3OHb4P4sgpaFdbuEgRnbT1vq0jLHxas7+PCrBZeA36UJgbaWA7PegQQqOj0IIBaxJzrSdbbqwxpC3W+w0VYZlaH2xG2wVPgMEczvNkep4D1LU3ziof9/OwBoP3aw4adX/irecUZweYoh/OS67aGxR2DFOIOURyFokfCPrDeToH/dJ4yjOKVDv vanessa.chaddouk@gmail.com
command="/usr/bin/tmux -L rookieclub attach",no-port-forwarding,no-X11-forwarding,no-agent-forwarding ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQCm9w9AEH9A4HrxTkOPcwR9IvuCw7zORtzCgTlkr3f/ILIJdgJSW3NRLjPvpm9mKVM/B4COd2yaldvnLvrlkY24ybqmAlSherVJD84sF6fkr/HJr4V8zYshzqnhZNM4g5ctO0oR27wlMYJAJMdLB+/3RekBKOoFhYGnjUbxZyk2UpUFqhGQWqQ3nTldfNslnVKkSl+M0ijC8s9eP0yrQDIS6W4NGTJWaAqxU5wWlcPyRSka27iekYa+MHMJuN2WrjznUj8DGFyymXfBZRyHkDosqCjeOIo6OCMNQltOp4xVZeqdnchIXGMXBomSTntz4Q+KINNY+5Uv5CY3MmUR23fx almeida.melanie@gmail.com
</pre>
