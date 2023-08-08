# ArduflipperOne
Arduflipper é um dispositivo Flipper baseado em Arduino, nada mais!
fiz isso porque vejo muita gente gostando das funções do Flipperzero ,
principalmente abrindo uma porta de carga de tesla e a função de clonagem de RF para dispositivos de RF simples.

![IMG_20221225_15362634r5](https://user-images.githubusercontent.com/20719445/210774538-07f84027-da5c-4b93-aead-fa06398cc496.jpg)

então, por enquanto, é chamado Arduflipper One porque temos uma função no momento,
já adicionou o suporte para BadUSB e IR blaster, (NÃO ESPAÇO SUFICIENTE dentro do Arduino Nano e Uno)
então, por enquanto, divirta-se abrindo as portas de carga Tesla e clone seu controle remoto RF e transmita.
Divirta-se, atualizarei quando puder


ArduFlipper one v1.01 Beta

ele armazenará 2 chaves na eeprom após receber uma ou 2.
terceira chave irá substituir a primeira chave novamente apenas 2 chaves cabem no máximo no armazenamento
ele também armazenará o tipo de taxa de bits da chave.
para usar as teclas armazenadas na memória. vá para o logotipo principal, pressione para a esquerda para usar o armazenamento 1 e para a direita para o armazenamento 2.
empurrar o joystick para cima transmitirá uma chave de ponto de carga Tesla
botão de pressão rápida enviará você para o menu.
no menu, pressione por 2 segundos para entrar no assunto selecionado.
RX ou TX ou VOLTAR.

vai tornar as coisas melhores, aproveite esta versão Beta.


para fazer um Arduflipper uma versão 1.01,

o que você precisa !

1 Arduino (nano or a uno ) 

![download (4)](https://user-images.githubusercontent.com/20719445/210767024-758f3b28-886a-4724-bd37-35992bebf89a.jpg)

atualizarei meu projeto para outro (Arduino Mega Mini) para Bad usb e todas as outras funções para caber.

1 tela oled 128x64 i2c SSD1306, (a cor que você preferir)

![download (2)](https://user-images.githubusercontent.com/20719445/210766292-b1a1427d-084e-433c-b7e5-55eb19ebbd40.jpg)

Para problemas de resolução de imagem
OBSERVAÇÃO ! (para a tela oled mude a resolução no arquivo Adafruit_SSD1306.H )

    #define SSD1306_128_64
   
// #define SSD1306_128_32

ou apenas copie e cole o Adafruit_SSD1306.H (incluído) sobre o original e recarregue seu esboço


1 Módulo transmissor e receptor de 433 Mhz .

![download](https://user-images.githubusercontent.com/20719445/210765297-00b1fe7e-c71d-4d87-af0a-19b12c4b3851.jpg)

1 joypad Arduino (irá atualizá-lo para botões no futuro)

![download (1)](https://user-images.githubusercontent.com/20719445/210766173-3ea37b9a-acb4-4f7b-8bef-a455aa8f3d12.jpg)

(Módulo Bluetooth BT HC-05/HC-06 opcional para o aplicativo DIY também disponibilizarei apenas para Android, porque é construído usando o inventor do MIT APP)

![download (3)](https://user-images.githubusercontent.com/20719445/210766449-b4e2159d-f46e-492d-b96a-377c3fd109bf.jpg)

E uma caixa para caber, fiz uma impressão 3D, também vou atualizar essa música e disponibilizá-la!

![IMG20230103145011](https://user-images.githubusercontent.com/20719445/210771874-05d3b8c1-cf02-4feb-a99e-f5ced7c6b473.jpg)
![IMG20230103145100](https://user-images.githubusercontent.com/20719445/210772371-4cd14c2e-b175-4388-a8e2-bf5cbbd46beb.jpg)
![IMG20230103145006](https://user-images.githubusercontent.com/20719445/210772512-0f5f2d3b-8ad7-4d5a-8af6-e21a3cd9d274.jpg)


Se o seu upload for um sucesso!
se você empurrar para cima, ele transmitirá um farol de ponto de carga Tesla duas vezes. (você verá o logotipo Tesla na tela)
se você pressionar o botão sw no joypad, você entrará no menu para controles remotos RX RF.

wil ad armazenamento eeprom para códigos recebidos, e um segundo menu!


![Arduflipper pin setup](https://user-images.githubusercontent.com/20719445/210862213-3f1c1e45-ea4c-42ae-8809-15828baefeb5.jpg)
