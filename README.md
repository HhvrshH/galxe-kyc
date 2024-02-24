# GALXE KYC AIO

Written by: @hvrsh (TG)

Channel: https://t.me/hashvers

---

**Automation on BAS for PASS making on Galxe**

**Setup when launching `phantom_aio.xml`:**

1. Use Finger Switcher - whether to use fingerprints.
   1. Finger Print Key - if **1** is enabled, you need to enter a key to obtain fingerprints, which can be purchased here - https://fingerprints.bablosoft.com/
2. Threads - number of threads launched simultaneously.
3. Clear DoneList - After successful completion or insufficient balance, private keys are written to the `done_list.txt` file so that the software understands which accounts it has passed and which ones it has not, in case you interrupt its work or the thread terminates with an error. If you need to rerun all wallets - select Yes.
4. Wallet shuffle - whether to shuffle wallets.
5. Proxy Type - proxy type.

 **Files for operation**

 `private.txt` - specify private keys.

 `proxy.txt` - proxies, selected line by line.

 **Results**

 `url_list.txt` - results. The link remains active for about 12 hours.

 `address_with_pass_list.txt` - addresses where Passport already exists.

 `pass_list.txt` - passwords for Passports.

 `small_bal_list.txt` - accounts that do not have enough balance for minting.
 

---

**Автоматизация на БАСе получения Паспортов на Galxe**

**Настройка при запуске `phantom_aio.xml`:**

1. Use Finger Switcher - использовать ли отпечатки.
	1. Finger Print Key - в случае включения **1** нужнно вести ключ для получения отпечатков, покупается тут - https://fingerprints.bablosoft.com/
2. Threads - количество потоков запущеных одновременно.
3. Clear DoneList - После успешного выполнения или отсутствия достаточного баланаса в файл `done_list.txt` записываются приватники, чтобы софт понимал какие аккаунты он прошел а какие нет, в случае если вы прервали его работу или поток завершится с ошибкой. Если нужно прогнать все кошельки заново - выбираем Yes.
4. Wallet shuffle - делать ли перемешивание кошельков.
5. Proxy Type - тип прокси.

 **Файлы для работы**

 `private.txt` - указывать приватники.

 `proxy.txt` - прокси, выбираюся построчно.

 **Результаты**

 `url_list.txt` - результаты. Ссылка остается рабочей около 12 часов.

 `address_with_pass_list.txt` адреса где уже есть Паспорт.

 `pass_list.txt` - пароли к Паспортам.

 `small_bal_list.txt` - аккаунты которым не хватит баланса для минта.