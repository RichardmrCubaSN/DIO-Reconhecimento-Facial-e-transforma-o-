# Reconhecimento-Facial-e-transformacao-de-imagens-em-Dados-no-Azure-ML
***DIO Reconhecimento Facial e transformação de imagens em Dados no Azure ML***

<br> 
O teste inicial tem a finalidade de testar os recursos do Estúdio de Visão da IA do Azure e para criar um recurso é necessário entrar no portal da Azure e clicar em <b>IA + Machine Learning</b>, em seguida, é só escolher a opção <b>Serviços Cognitivos</b> (se a página estiver em português) ou <b>Azure AI Services</b> (se a página estiver em inglês), para então clicar em <b>Criar(Criate)</b>.<br>

<b><i>OBS:</i></b> Esse procedimento fará uma ponte do serviço de inteligência artificial na assinatura do Azure para o Visual Studio (Estúdio de Visão).<br>
<br>
A subscrição já vem preenchida e não há necessidade de alterar, então basta escolher(caso já tenha feito) ou criar(caso ainda precise criar) o <b>Resource Group (Grupo de recursos)</b>, depois é só escolher a região e um nome de sua preferência. Em seguida, ir em <b>Pricing tier (Tipo de preço)</b> e selecionar <b>Standard S0</b>, para então ticar a caixinha confirmando que leu e compreendeu os termos de aviso de responsabilidade da IA, para então <b>Examinar + criar (Review + create)</b> para que o recurso seja criado.<br>
<br>
Findada essa primeira parte, é necessário acessar o portal de visão ([portal.vision.cognitive.azure.com/gallery/featured](url)) e selecionar o recurso que acabou de criar. Após selecionar, fechar no x no canto superior direito da tela, o que o fará voltar à tela inicial para que então, escolha o estúdio em que vai trabalhar. <br>
Neste recurso, o primeiro teste foi feito com detecção de face, foi clicado em <b>Face</b> e foi possível enviar as imagens anexadas no arquivo inputs, nas quais a IA conseguiu identificar o atributo da imagem e já trazer o código JSON, descrevendo as imagens e mostrando o código.<br>
<br>

![teste face Mulher Input](https://github.com/RichardmrCubaSN/DIO-Reconhecimento-Facial-e-transforma-o-/blob/main/Inputs/store-camera-1A.jpg)
![teste face Mulher Output](https://github.com/RichardmrCubaSN/DIO-Reconhecimento-Facial-e-transforma-o-/blob/main/Outputs/store-camera-1.png)


<br>
A segunda parte do teste, analisou textos presentes em imagens, identificando as palavras e dando o código JSON. Tal funcionalidade, permite analisar documentos através do reconhecimentos de caracteres, que extrai das imagens tudo que é texto, independente se é letra escrita à mão ou impressa. Para fazer esse teste, basta ir em <b>Optical character recognition</b> e enviar a foto que quer analisar.<br>
<br>

![teste palavra na foto Input](https://github.com/RichardmrCubaSN/DIO-Reconhecimento-Facial-e-transforma-o-/blob/main/Inputs/advert.jpg)
![teste palavra na foto Output](https://github.com/RichardmrCubaSN/DIO-Reconhecimento-Facial-e-transforma-o-/blob/main/Outputs/advert.png)

<br>

<br>
A terceira parte, por sua vez, se deu com a análise de imagens, tendo cenários identificados. Para realizar o teste, basta voltar a página inicial do vision studio, clicar em <b>Image analysis</b>, em seguida, em Add captions to images, para então enviar a foto que deseja analisar e receber a análise, junto com o código JSON.
<br>

![analise de cenario Input](https://github.com/RichardmrCubaSN/DIO-Reconhecimento-Facial-e-transforma-o-/blob/main/Inputs/store-camera-1B.jpg)
![analise de cenario Output](https://github.com/RichardmrCubaSN/DIO-Reconhecimento-Facial-e-transforma-o-/blob/main/Outputs/store-camera-1-output.jpg)


<br>
<h2>Liks Importantes:</h2>

<br>

[https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html](url)

<br> 

[https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html](url)

<br> 

[https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html](url)
