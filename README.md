from random import *
answer = ['Бесспорно','Мне кажется - да','Пока неясно', 'Попробуй снова','Даже не думай','Предрешено','Вероятнее всего','Спроси позже','Мой ответ - нет','Никаких сомнений','Хорошие перспективы','Лучше не рассказывать','По моим данным - нет','Определённо да','Знаки говорят - да','Сейчас нельзя предсказать','Перспективы не очень хорошие','Можешь быть уверен в этом','Да','Сконцентрируйся и спроси опять','Весьма сомнительно']
print('Привет Мир, я магический шар, и я знаю ответ на любой твой вопрос.')
print('Как я могу к вам обращаться?')
name=input()
print('Привет,',name)
n=8
while n == 8:
    print('Введите ваш вопрос')
    с=input()
    print(choice(answer))
    print('Чтобы задать еще вопрс,введите цифру 8')
    n = int(input())
print('Возвращайся если возникнут вопросы!')
