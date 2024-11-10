o nosso projeto se divide em 2 seguimentos o bot e o hardware físico ambos ultlizado a api médico one(api própria que desenvolvemos) que faz todas as operações descritas a baixo em relação a processamento 

passo a passo 

1. O paciente abre o chat (podendo ser próprio ou de terceiros)

2. uma requisição é iniciada aonde o usr informa dados pessoais para o cadastro ou acessa o cadastro de terceiros (SUS, convênios, etc)

3 o bot faz como primeira pergunta se o caso é urgente caso seja o bot faz um loop de perguntas reduzidas e indica o hospital mais próximo 

4. o bot faz um loop de perguntas para coletar informações de relevância médica

5. dentro do loop o bot pergunta se o usr sabe suas informações vitais como temperarura pressão etc caso o usr não saiba ele pode responder "não sei" ou "pular todas as perguntas"

6. dentro do loop é perguntado se possui médico se interesse casa não aja o bot chama a api do gpt ou de terceiros(IA) concatena as informações coletadas e passa um prompit para sugerir um médico. é mostrado ao usr que é apenas uma recomendação a qual nao responsabilisa o bot por eventuais erros 

7. o bot pergunta se o usr quer marcar uma consulta caso a resposta seja positiva o bot marca a consulta e informa o usr do dia e local ou caso seja no mesmo dia o lugar só usr na fila 



* essa solução pode ajudar a diminuir as filas e fazer os pacientes entenderem melhor os sintomas

o hardware físico 

inspirado nós totens de autoatendimento de festfood que entregam velocidade e qualidade tem se a segunda via do projeto 


1. quando o usr chega no hospital já direcionando para um totem que podem ser colocado um do lado do outro 

2. o usr inicia uma requisição aonde o totem mostra uma tela perguntado se o caso seria urgente caso seja o totem despara o aviso de urgência do hospital e caso o hospital não tenha uma enfermeira é chama 

3. caso não seja urgente o totem segui com o mesmo loop de perguntas do bot 

4. o diferencial principal do totem com o bot é que o totem possui equipamentos para fazer as medições de sinais vitais fazendo o processo de pre triagem automatizado permitindo com que o trabalho de vários enfermeiros seja feito ali no totem poupando tem e otimizando processos 

5. o usr pega os equipamentos que possui giroscópios nas pontas permitindo com q o totem saiba caso o usr pegou o equipamento errado 

6. cada equipamento possui um vídeo testo e animação de como deve ser usado de maneira correta 


7. ao final o totem envia as informações para o server do hospital ou para o médico por email chat etc 

8 por fim o totem mostra a opção de imprimir todas as informações coletadas ou gerar um Qr para um pdf que possa ser levado para o médico 

