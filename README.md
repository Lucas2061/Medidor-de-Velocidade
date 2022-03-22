# Medidor-de-Velocidade


Taking into account the maximum speed allowed of 80km on a given street. Create a program that receives from the user a value that represents the speed and based on that speed, tell if she got a light, serious or very serious fine. Taking into account that if the person is below the maximum speed, your program should display "there was no fine", if it is up to 10 km above, it should display: "Took a light fine" if it is between 11 to 20 km above the maximum speed, display: " Got a serious fine", and if you are over 20km above the maximum speed, display: "Took a very serious fine"

Critically analyze the problem and discover:
(Try explaining this problem to yourself out loud and ask for more information/investigate until you fully understand the problem.)

1. What input data is required?
- Speed
2. What should I do with this data?
- Taking into account that if the person is below the maximum speed, your program should display "there was no fine", if it is up to 10 km above, it should display: "Took a light fine" if it is between 11 to 20 km above the maximum speed, display: "Took a serious fine", and if you are over 20km above the maximum speed, display: "Took a very serious fine"
3. What are the constraints of this problem?
- Not found
4. What is the expected result?
- The expected result is to display the message that corresponds to the level of the fine that the person took (display: "Took a light fine" if it is between 11 to 20 km above the maximum speed, display: "Took a serious fine", and if it is above 20km above the maximum speed, display: "He got a very serious fine")
5. What is the sequence of steps to be taken to reach the expected result?
input speed
max_speed = 80
if speed => maximum_speed:
  print'no fine'
if speed > max_speed and speed <= max_speed + 10:
  print"Took a light fine"
if speed > max_speed + 11 and speed <= max_speed + 20:
  print"Took a serious fine"
if speed > max_speed + 20:
  print"Took a very serious fine"
  
  <h1>Traduzido em Português</h1>
  
  Levando em consideração a valocidade máxima permitida de 80km em uma determinada rua. Crie um programa que recebe do usuário um valor que representa a velocidade e com base nessa velocidade diga se ela tomou uma multa leve, grave ou grávissima. Levando em consideração que se a pessoa estiver abaixo da velocidade máxima seu programa deve exibir "não houve multa", caso esteja até 10km acima, deve exibir: "Levou multa leve" caso esteja entre 11 a 20km acima da velocidade máxima, exibir: "Levou multa grave", e caso esteja acima de 20km acima da velocidade máxima, exiba: "Levou multa gravíssima"

Analise críticamente o problema e descubra:
(tente explicar este problema para você mesmo em voz alta e peça mais informações/investigue mais até você compreender completamente o problema.)

1. Quais são os dados de entrada necessários?
- Velocidade
2. O que devo fazer com estes dados?
- Levando em consideração que se a pessoa estiver abaixo da velocidade máxima seu programa deve exibir "não houve multa", caso esteja até 10km acima, deve exibir: "Levou multa leve" caso esteja entre 11 a 20km acima da velocidade máxima, exibir: "Levou multa grave", e caso esteja acima de 20km acima da velocidade máxima, exiba: "Levou multa gravíssima"
3. Quais são as restrições deste problema?
- Não encontrado
4. Qual é o resultado esperado?
- O resultado esperado é exibir a mensagem que corresponde ao nível da multa que a pessoa levou (exibir: "Levou multa leve" caso esteja entre 11 a 20km acima da velocidade máxima, exibir: "Levou multa grave", e caso esteja acima de 20km acima da velocidade máxima, exiba: "Levou multa gravíssima")
5. Qual é a sequencia de passos a ser feitas para chegar ao resultado esperado?
input velocidade
velocidade_maxima = 80
if velocidade => velocidade_maxima:
  print'não levou multa'
if velocidade > velocidade_maxima e velocidade <= velocidade_maxima + 10:
  print"Levou multa leve"
if velocidade > velocidade_maxima + 11 e velocidade <= velocidade_maxima + 20:
  print"Levou multa grave"
if velocidade > velocidade_maxima + 20:
  print"Levou multa gravíssima"
