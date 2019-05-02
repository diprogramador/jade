# jade 


import sys
import os
import pyttsx3

r = sys.platform
print(r)



n = input("Digite seu nome: ")

fala = pyttsx3.init()
fala.setProperty('voice', b'brazil')
fala.say(n)
fala.runAndWait()


fala = pyttsx3.init()
fala.setProperty('voice', b'brazil')
fala.say("A baixo você tem um guia sobre em que posso te ajudar, digite um numero: ")
fala.runAndWait()
print("A baixo você tem um guia sobre em que posso te ajudar, digite um desses comandos: \n")


fala = pyttsx3.init()
fala.setProperty('voice', b'brazil')
fala.say("wordpad 1, virtualdj 2, chrome 3, youtube 4, facebook 5, whatzapp 6, discord 7, criador 8")
fala.runAndWait()
print("wordpad (1) / virtualdj (2), chrome (3), youtube (4) / facebook (5) / whatzapp (6) / discord (7) / criador (8) \n")

fala = pyttsx3.init()
fala.setProperty('voice', b'brazil')
fala.say("arduino 9, tabela de cores 10, mr.robot 11, conversor de pdf 12, projetar 13, webhost 14")
fala.runAndWait()
print("arduino (9) / tabela de cores (10) / mr.robot (11) / conversor de pdf (12) / projetar (13) / webhost (14)\n")

fala = pyttsx3.init()
fala.setProperty('voice', b'brazil')
fala.say("github 15, blockchain 16, word 17, rastrear dispositivo 18")
fala.runAndWait()
print("github (15) /  blockchain (16) / word (17) / rastrear dispositivo (18)\n")

while True:

    resp = str(input("digite: "))

    if resp == '1':
        os.startfile("wordpad")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo wordpad")
        fala.runAndWait()

    if resp == '2':
        os.startfile("virtualdj8")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo virtual Dj")
        fala.runAndWait()

    if resp == '3':
        os.startfile("chrome")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo chrome")
        fala.runAndWait()

    if resp == '4':
        os.startfile("https://www.youtube.com/")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo You Tube")
        fala.runAndWait()    

    if resp == '5':
        os.startfile("https://www.facebook.com/")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo Facebook")
        fala.runAndWait()
        
    if resp == '6':
        os.startfile("https://web.whatsapp.com/")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo whatzapp web")
        fala.runAndWait()
        
    if resp == '7':
        os.startfile("https://discordapp.com/activity")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo discord")
        fala.runAndWait()

    if resp == '8':
        os.startfile("http://blogpythonlimeira.000webhostapp.com/")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo site do meu criador")
        fala.runAndWait()
        
    if resp == '9':
        os.startfile("https://auth.arduino.cc/login/?challenge=eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJhdWQiOiJjcmVhdGUiLCJleHAiOjE1NTY2NzE2MjAsImp0aSI6IjZkZWJiZWQwLTBkNDEtNDZkZC05MDU2LTNjNzUwOWZkMWJlYiIsInJlZGlyIjoiaHR0cHM6Ly9oeWRyYS5hcmR1aW5vLmNjL29hdXRoMi9hdXRoP2NsaWVudF9pZD1jcmVhdGVcdTAwMjZzdGF0ZT1lb2I0M3Fsalx1MDAyNnNjb3BlPXByb2ZpbGU6Y29yZSUyMHByb2ZpbGU6Y29udGFjdCUyMHByb2ZpbGU6cHVibGljJTIwY3JlYXRlOnVzZXJzJTIwY3JlYXRlOnNrZXRjaGVzJTIwY3JlYXRlOmZpbGVzJTIwY3JlYXRlOmxpYnJhcmllcyUyMGNyZWF0ZTpjb21waWxlJTIwaW90OmRldmljZXMlMjBwcm9maWxlOmFkZHJlc3MlMjBwcm9maWxlOnByaXZhdGVcdTAwMjZyZXNwb25zZV90eXBlPXRva2VuXHUwMDI2cmVkaXJlY3RfdXJpPWh0dHBzJTNBJTJGJTJGY3JlYXRlLmFyZHVpbm8uY2MiLCJzY3AiOlsicHJvZmlsZTpjb3JlIiwicHJvZmlsZTpjb250YWN0IiwicHJvZmlsZTpwdWJsaWMiLCJjcmVhdGU6dXNlcnMiLCJjcmVhdGU6c2tldGNoZXMiLCJjcmVhdGU6ZmlsZXMiLCJjcmVhdGU6bGlicmFyaWVzIiwiY3JlYXRlOmNvbXBpbGUiLCJpb3Q6ZGV2aWNlcyIsInByb2ZpbGU6YWRkcmVzcyIsInByb2ZpbGU6cHJpdmF0ZSJdfQ.J5FKa0hswn3e-yb0U3t5SYwU98kygcG741uTEGwmEWXHmYV8rXgXCZwcH9YUsTLGCLQzsBmwIAkfcemADVggnafgHYhun442K3yq0sFZCtrruyM1yg-F3Uy2jchwyQlpj_qdfaqfyWSA31kUFFFDZemtmhAf0acvFZXGq8h6ZsfP95Ayo4FHGaTXfzA4nb1TybqYnpqkm1LDZ4IdeUgo3j5r2r4EzFufDP6TxETORgQnCRL4Lt2isWthYJ9y9FPwbE-YSF_9ZoVjxn0M7kV6qc4Oq-bhwbEg21PU7czlh3ma7w648e1NOPpkf_KKLptetVokq2kSmn1is2AvtOEQDrb-lJ2fBX6tkAhIhmPnEj9QPvQD9ZKy2VvqLqu4zSxCI3o-RjfhDI3uEZA9iuWIrQpC3q7hITCDthgJzWhsw7Snpdu68j2x9tV1_wCizjy4JJ_wudDKE2zBR8Q-GV2xcJw2e_UYZE-sH2KB1OwAbvEnzXHbuI1-hg9EQ2KuOaI6ld6Z8Zf7qbH6N81fGwaA1_b03IB24gT4LqAWpmayKk3NbLFLTix2HjZM2qbzXOf5Ju5swwKpNFNVUMGOULY1gjCAMmrBWvMlYQnlIJ1oOWZgQ78S59IYpPusayjP_pZCqPz4DiJ_vs9TsIEHqZD9q5tdD3g6BwN5RTJl7nW7dx4")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrido Arduino")
        fala.runAndWait()
        
    if resp == '10':
        os.startfile("http://erikasarti.com/html/tabela-cores/")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo Site de códigos de cores")
        fala.runAndWait()
        
    if resp == '11':
        os.startfile("http://zseriesonline.com/assistir-mr-robot-online-gratis/")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Chega de trabalho por hoje Doutor, Partiu relaxar assistir uma boa série")
        fala.runAndWait()
        
    if resp == '12':
        os.startfile("https://www.freepdfconvert.com/pt")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo site de conversão de PDF")
        fala.runAndWait()
        
    if resp == '13':
        os.startfile('https://www.tinkercad.com/things/e54ix5dSKaN-start-simulating/editel?collectionid=OIYJ88OJ3OPN3EA&lessonid=EHD2303J3YPUS5Z&magic=582c772b2ab00f51f6d04edc3def76d1891d5c85&projectid=OIYJ88OJ3OPN3EA&t=1552833553400593257&tenant=circuits#/lesson-viewer')
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo Área de projetos")
        fala.runAndWait()
        
    if resp == '14':
        os.startfile('https://br.000webhost.com/login-cpanel?from=panel')
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo hospedagem de site")
        fala.runAndWait()
        
    if resp == '15':
        os.startfile('https://github.com/session')
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo site github")
        fala.runAndWait()
        
    if resp == '17':
        os.startfile("https://login.blockchain.com/#/login")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo blockchain")
        fala.runAndWait()
        
    if resp == '18':
        os.startfile("https://office.live.com/start/Word.aspx?s=1&auth=1&nf=1#")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo word 360")
        fala.runAndWait()
        
    if resp == '19':
        os.startfile("https://office.live.com/start/Word.aspx?s=1&auth=1&nf=1#")
        fala = pyttsx3.init()
        fala.setProperty('voice', b'brazil')
        fala.say("Abrindo rastreamento de dispositivo")
        fala.runAndWait()

    if resp == 'tchau':
            en = pyttsx3.init()
            en.setProperty('voice', b'brazil')
            frase = en.say('Entrando em quárentena! Estarei em Sentinéla!. ')
            en.runAndWait()        
            break 
