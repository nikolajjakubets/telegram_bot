# telegram_chat_bot
Телеграмм бот на Python (Bit)  
Я новичок в питоне, так что вы все понимаете прекрасно ...  
  
    
Python 3.7.3  
pyTelegramBotAPI==3.6.6  
telebot==0.0.3
  
Вписываешь свой токен в файл бота и запускаешь, отвечает строго по шаблону, есть фильтр символов, так же черный список. (токен полученый у @BotFather)  
  
Бот 'bit-15.3.py' запускается на любой операционной системе, сам пробовал на Windows и Linux. (как обычный скрипт)  
  
Отвечает только на то, что и как написано в базе с ответами 'base_answer.py', советую при редакции ответов придерживаться шаблона " tuple(["вопрост","вопрос"]):['ответ','ответ'] "  
  
При отправки сообщения боту он записывает в файл 'log.txt' параметры: "пользователь, сообщение [время] [айди]"  
  
По айди можно выдать бан, просто записать айди пользователя в файл 'blacklist.py'  
  
Ну вот и все, если что то упустил извеняюсь, можете написать мне в {"inst":0bezynka, "vk":id457701993}  
Буду очень рад если кто то смышленный его возьмет и улучшит, кому то он хоть как то пригодится)  
Всего хорошего тебе и успехов)
Я не игнорщик, просто ушел в армию)))
