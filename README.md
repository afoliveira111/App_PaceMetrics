# PaceMetrics
## Desenvolvido na HackSprint em Squad.
Aplicativo que calcula o Ritmo e salva seu histórico!


## :camera_flash: Screenshots
<!-- You can add more screenshots here if you like -->

<table>
  <tr>
    <td><img src="/result/Screenshot_splashscreen.png" width="260"></td><td><img src="/result/Screenshot_1.png" width="260"></td><td><img src="/result/Screenshot_2.png" width="260">
  </tr>
</table>



## Tecnologias Utilizadas


* Kotlin
* Activity para host de telas
* ViewGroup
    * RelativeLayout
    * LinearLayout
       
- Components de UI
    - TextView
    - EditText
    - Button
      
- Toast para display de mensagens
- Intent Explicita para abrir a segunda Activity
- FindViewById para recuperar components de UI
- String resource para concatenação de textos
  
    
- # **Arquitetura e Padrões de Projeto:**
  - MVVM (Model-View-ViewModel)
  - Clean Architecture

- **Controle de Versão:**
  - GitHub

- **Metodologia:**
  - SCRUM

- **Bibliotecas e Frameworks:**
  - Coroutine para programação assíncrona

- **Android SDK:**
  -  Lifecycle
  -  LiveData
  -  ViewModel 

- **Persistência de Dados:**
  - Room Database para armazenar e recuperar informações, integrando-o com REST APIs

## Funcionalidades Principais

1. **Cálculo de Pace:**
   - O aplicativo permite o cálculo do pace médio com base na distância percorrida e no tempo.

2. **Histórico de Paces:**
   - Visualização do histórico de paces registrados.

3. **Splash Screen:**
   - Uma tela inicial (Splash Screen) é exibida por dois segundos antes de direcionar para a tela principal.

## Estrutura do Projeto

O projeto está organizado em diferentes pacotes, cada um responsável por uma parte específica da aplicação:

- **presentation:** Contém as classes relacionadas à interface do usuário.
- **data:** Classes relacionadas à camada de dados, como o banco de dados e a manipulação de dados.



## TODO

- Melhorar a estilização do aplicativo.
  
- Adicionar novas funcionalidades.

- GPS

- Mapa

  

## Autor
Antonio Felipe Oliveira (www.linkedin.com/in/id-antonio-felipe)

## License

The MIT License (MIT)

Copyright (c) 2023 Antonio Felipe Oliveira

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN






