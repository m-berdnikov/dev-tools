### Генерация ключа SSH для GitHub, GitLab, BitBucket и т.д.

Откройте терминал и выполните команду:

```
ssh-keygen -t rsa
```

На консоль будет выведен следующий диалог:

```
Enter file in which to save the key (/home/user/.ssh/id_rsa):
```

Нажмите на клавишу Enter. Далее система предложит ввести кодовую фразу для дополнительной защиты SSH-подключения:

```Enter passphrase (empty for no passphrase):

```

Этот шаг можно пропустить. При ответе на этот и следующий вопрос просто нажмите клавишу Enter.

После этого ключ будет создан, а на консоль будет выведено следующее сообщение:

```
Your identification has been saved in /home/user/.ssh/id_rsa.
Your public key has been saved in /home/user/.ssh/id_rsa.pub.
The key fingerprint is:
476:b2:a8:7f:08:b4:c0:af:81:25:7e:21:48:01:0e:98 user@localhost

The key's randomart image is:

+--[ RSA 2048]----+

|+.o.             |

|ooE              |

|oo               |

|o.+..            |

|.+.+..  S .      |

|....+  o +       |

|  .o ....        |

|  .  .. .        |

|    ....         |

+-----------------+
```

Далее выполните в терминале команду:

```
cat ~/.ssh/id_rsa.pub
```

На консоль будет выведен ключ. Скопируйте его и вставьте в соответствующее поле в нужном сервисе.
