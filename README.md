# 123
import telebot

bot = telebot.TeleBot("1164510001:AAG7E_j8YoDRFta_M7RMs8jKOstClCFACos")

@bot.message_handler(content_types=['text'])
def send_echo(message):
	bot.send_message(message.chat.id, messega.text)

bot.polling( none_stop = True )

