from plus import podkl
class Lololo:
    name = 'levelBot'
    def __init__(self,Priolj,Login,Porol):
        self.pr = Priolj
        self.l = Login
        self.p = Porol
    def fro(self):
        return podkl(self)

    def fax(self):
        print(f'''Привет это образавательный центр Level''')
        return self.list()
    def list(self):
        print('''1) Уроки
2) Учителя
3) Записатся на урок
4) О нас
5) Связатся с оператроm''')
        q = input('Choose one:')
        if q == '1':
            return self.uroki()
        elif q == '2':
            return self.uchtelya()
        elif q == '3':
            return self.zapuroki()
        elif q == '4':
            return self.onas()
        elif q == '5':
            return self.svyaz()





    def uroki(self):
        print(f'''1) Математика
2) Программирование
3) Англиский''')
        p = input('Choose  one: ')
        if p == '1':
            return self.matema()
            z = input('Если хотите назад то напишите:0\n ---')
            if z == '0':
                return self.uroki(self)
        elif p == '2':
            return self.prog()
        elif p == '3':
            return self.anglis()

    def matema(self):
        print('''Математика -- за месяц 20000
Учитель матиматики Султан Нурислам''')
        z = input('Если хотите назад то напишите:0\n ---')
        if z == '0':
            return self.list()


    def prog(self):
        print('''Программирование -- за месяц 25000
Учитель программирование Табигат Карбаев''')
        z = input('Если хотите назад то напишите:0\n ---')
        if z == '0':
            return self.list()

    def anglis(self):
        print('''Англиский -- за месяц 15000
Учитель англиского Нурсулу Айткызы''')
        z = input('Если хотите назад то напишите:0\n ---')
        if z == '0':
            return self.list()

    def uchtelya(self):
        print(f'''1) Табигат Карбаев
2) Султан Нурислам
3) Нурсулу Айткызы''')
        z = input('Если хотите назад то напишите:0\n ---')
        if z == '0':
            return self.list()
    def zapuroki(self):
        print(f'''1) Математика
2) Программирование
3) Англиский
На что хотите записатся''')
        w = input('Choose one: ')
        if w == '1':
            return self.matem1()
        elif w == '2':
            return self.program1()
        elif w == '3':
            return self.ang1()
    def matem1(self):
        print('''Уроки будут в 6 вечера в приложении зум
Ждите ссылку''')
        z = input('Если хотите назад то напишите:0\n ---')
        if z == '0':
            return self.list()
    def program1(self):
        print('''Уроки будут в 7 вечера в приложении зум
Ждите ссылку''')
        z = input('Если хотите назад то напишите:0\n ---')
        if z == '0':
            return self.list()
    def ang1(self):
        print('''Уроки будут в 8 вечера в приложении зум
Ждите ссылку''')
        z = input('Если хотите назад то напишите:0\n ---')
        if z == '0':
            return self.list()
    def onas(self):
        print('Наш центр открылся в 2019 году и открыл его Табигат Карбаев')
        z = input('Если хотите назад то напишите:0\n ---')
        if z == '0':
            return self.list()
    def svyaz(self):
        print(f'''Вы тут можете сообщять своии проблемы
1) Не можете запистся
2) По больше узнать наших учителей
3) По больше узнать о уроках''')

        e = input('Выберите число: ')
        if e == '1':
            print('ссылку можете плучить в телерамм канале канал PythonLevel')
            z = input('Если хотите назад то напишите:0\n ---')
            if z == '0':
                return self.list()
        elif e == '2':
            print('''Табигат Карбаев 20 лет учится в СДУ
Султан Нурислам 20 лет в учится МУИТ
Нурсулу Айткызы 21 лет в учится МУИТ''')
            z = input('Если хотите назад то напишите:0\n ---')
            if z == '0':
                return self.list()
        elif e == '3':
            print('Уроки будут проходить онлайн через зум а ссылка в телеграмм канале')
            z = input('Если хотите назад то напишите:0\n ---')
            if z == '0':
                return self.list()
        else:
            while e != '1' or '2' or '3':
                return self.svyaz()

        z = input('Если хотите назад то напишите:0\n ---')
        if z == '0':
            return self.list()



r = Lololo('Telegram','mahmud07','mahmud2007')
r.fro()



def podkl(self):
    a = input('Login pls:')
    b = input('Porol pls:')
    if a == self.l and b == self.p:
        return self.fax()

    else:
        while a != self.l and b != self.p:
            return print(f'ne pravilno povtarite \n{self.podkl()}')
