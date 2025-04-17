<h1>Projeto Vinheria Agnello</h1>
<strong>Este projeto tem como objetivo o desenvolvimento de um sistema de monitoramento de luminosidade para uma vinheria, garantindo que os vinhos sejam armazenados em condições ideais de iluminação, já que à luz excessiva pode comprometer a qualidade dos vinhos, por isso é essencial manter os níveis de luminosidade sob controle.</strong>

 <a href="https://youtu.be/gdGriPKhJOs" target="_blank"> "Explicação sobre o projeto"</a>

<h2>Níveis de luminosidade e sistema de aviso</h2>

<h3>LED Verde: Nível de luminosidade OK.</h3>
<h3>LED Amarelo: Nível de alerta.</h3>
<h3>LED Vermelho: Nível crítico ou problema.</h3>
<h3>Buzzer: Ativado por 3 segundos quando a luminosidade estiver em nível de alerta.</h3>


<h2>Componentes Utilizados</h2>

<li>Arduino Uno</li>

<li>1x Sensor LDR</li>

<li>1x Resistor de 10kΩ (para o LDR)</li>

<li>1x LED Verde</li>

<li>1x LED Amarelo</li>

<li>1x LED Vermelho</li>

<li>3x Resistores de 220Ω (para os LEDs)</li>

<li>1x Buzzer</li>

<li>Jumpers e Protoboard</li>


<h3>Plataformas utilizadas</h3>
<li>TinkerCad</li>


<h2>Como Reproduzir o Projeto:</h2>

<h3>utilize a imagem a seguir como um guia de montagem</h3>

![Recrie](./images/imagem.jpg)

<li>Crie uma conta ou entre em sua conta existente em: tinkercad.com</li>

<li>Adicione os componentes listados acima.</li>

<li>Configure o sensor LDR com um resistor de 10kΩ formando um divisor de tensão conectado a uma entrada analógica (ex: A0).</li>

<li>Ligue os LEDs e o buzzer em pinos digitais.</li>

<li>Implemente o código:</li>

![Recrie](./images/WhatsApp%20Image%202025-04-16%20at%2021.39.26.jpeg)

<li>Insira o código de controle com analogRead para o LDR, digitalWrite para os LEDs e tone() para o buzzer.

<li>Defina os limiares de luminosidade para os estados "OK", "Alerta" e "Crítico".</li>

<li>Inicie a simulação: Clique em "Start Simulation" e ajuste manualmente a luminosidade do LDR no Tinkercad para testar os comportamentos.</li>
