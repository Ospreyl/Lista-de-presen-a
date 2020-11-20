# Lista-de-presen-a
Presenças exemplo
#Lista de presença
import datetime
from datetime import datetime

# data_atual = date.today('%d/%m/%Y %H:%M')
data_e_hora_atuais = datetime.now()
data_e_hora_em_texto = data_e_hora_atuais.strftime('%d/%m/%Y')

nome = str(input('Digite seu nome completo :'))
produto = str(input('Qual é seu produto? :'))
matricula = int(input('Sua matricula:'))
print('{} '.format(nome))
print('Produto: {}'.format(produto))
print('matricula: {}'.format(matricula))
print('O Aluno {}, da matricula {} esteve presente na aula do dia {}'.format(nome,matricula, data_e_hora_em_texto))
