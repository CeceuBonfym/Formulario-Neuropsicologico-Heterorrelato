
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Questionário Neuropsicológico – Heterorrelato (Adulto)</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 20px;
            max-width: 900px;
            margin-left: auto;
            margin-right: auto;
            background-color: #f9f9f9;
            color: #333;
        }
        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 20px;
        }
        .psi-symbol {
            font-size: 60px;
            font-weight: bold;
            color: #2c3e50;
        }
        .contact-info {
            text-align: right;
            font-size: 14px;
            color: #555;
        }
        h1 {
            text-align: center;
            font-size: 24px;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        .instructions {
            margin-bottom: 20px;
            font-size: 14px;
            background-color: #fff;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        .form-field {
            margin-bottom: 15px;
            display: flex;
            align-items: center;
        }
        .form-field label {
            display: inline-block;
            width: 200px;
            font-weight: bold;
            color: #333;
        }
        .form-field input, .form-field select {
            padding: 8px;
            width: 300px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 14px;
        }
        .form-field input[type="text"]:focus {
            border-color: #4CAF50;
            outline: none;
        }
        .form-field.radio {
            align-items: center;
        }
        .form-field.radio input {
            width: auto;
            margin-right: 10px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
            background-color: #fff;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
            font-size: 14px;
        }
        th {
            background-color: #f2f2f2;
            font-weight: bold;
            color: #333;
        }
        .checkbox {
            width: 30px;
            text-align: center;
        }
        .checkbox input {
            transform: scale(1.2);
        }
        .footer {
            text-align: center;
            font-size: 12px;
            color: #777;
            margin-top: 20px;
        }
        .button-container {
            text-align: center;
            margin: 20px 0;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin: 0 10px;
        }
        button:hover {
            background-color: #45a049;
        }
        .whatsapp-share {
            background-color: #25D366;
        }
        .whatsapp-share:hover {
            background-color: #20B35A;
        }

        /* Estilos para impressão */
        @media print {
            body {
                background-color: white;
                margin: 10mm;
                max-width: 100%;
            }
            .button-container, .whatsapp-share {
                display: none;
            }
            .header, .contact-info, h1, .instructions, table, .footer {
                color: black;
            }
            table {
                box-shadow: none;
                font-size: 12pt;
            }
            .form-field input {
                border: none;
                border-bottom: 1px solid black;
                background-color: transparent;
            }
            .checkbox input {
                display: none;
            }
            .checkbox::before {
                content: "[ ]";
                font-size: 12pt;
            }
            .instructions {
                box-shadow: none;
                background-color: transparent;
                padding: 10px 0;
            }
            @page {
                size: A4;
                margin: 10mm;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="psi-symbol">Ψ</div>
        <div class="contact-info">
            <strong>Najila Khatab</strong><br>
            Psicóloga Clínica<br>
            CRP: 01/22736
        </div>
    </div>
    <h1>Questionário Neuropsicológico – Heterorrelato (Adulto)</h1>

    <form id="questionarioForm" action="https://form.jotform.com/form/xxxxxxxx" method="POST">
        <div class="form-field">
            <label>Nome do avaliado:</label>
            <input type="text" name="nome_avaliado" placeholder="                    " required>
        </div>
        <div class="form-field">
            <label>Data de nascimento:</label>
            <input type="text" name="dia_nasc" placeholder="  " style="width: 50px;" required> /
            <input type="text" name="mes_nasc" placeholder="  " style="width: 50px;" required> /
            <input type="text" name="ano_nasc" placeholder="    " style="width: 70px;" required>
        </div>
        <div class="form-field">
            <label>Data da avaliação:</label>
            <input type="text" name="dia_aval" placeholder="  " style="width: 50px;" required> /
            <input type="text" name="mes_aval" placeholder="  " style="width: 50px;" required> /
            <input type="text" name="ano_aval" placeholder="    " style="width: 70px;" required>
        </div>
        <div class="form-field radio">
            <label>Sexo:</label>
            <input type="radio" name="sexo" value="M" required> M
            <input type="radio" name="sexo" value="F"> F
        </div>
        <div class="form-field">
            <label>Nome do respondente:</label>
            <input type="text" name="nome_respondente" placeholder="                    " required>
        </div>

        <div class="instructions">
            <strong>Instruções:</strong><br>
            Leia atentamente cada item e marque com um X a opção que melhor descreve o comportamento da pessoa nos últimos 6 meses.<br>
            <strong>As opções são:</strong><br>
            1️⃣ Não é verdade<br>
            2️⃣ Algumas vezes é verdade<br>
            3️⃣ Muitas vezes é verdade<br>
            4️⃣ Quase sempre é verdade
        </div>

        <table>
            <thead>
                <tr>
                    <th>Nº</th>
                    <th>1️⃣</th>
                    <th>2️⃣</th>
                    <th>3️⃣</th>
                    <th>4️⃣</th>
                    <th>Item</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>1</td><td class="checkbox"><input type="radio" name="q1" value="1" required></td><td class="checkbox"><input type="radio" name="q1" value="2"></td><td class="checkbox"><input type="radio" name="q1" value="3"></td><td class="checkbox"><input type="radio" name="q1" value="4"></td><td>Parece muito mais desconfortável em situações sociais do que quando está sozinho(a).</td></tr>
                <tr><td>2</td><td class="checkbox"><input type="radio" name="q2" value="1" required></td><td class="checkbox"><input type="radio" name="q2" value="2"></td><td class="checkbox"><input type="radio" name="q2" value="3"></td><td class="checkbox"><input type="radio" name="q2" value="4"></td><td>As expressões em seu rosto não combinam com o que está dizendo.</td></tr>
                <tr><td>3</td><td class="checkbox"><input type="radio" name="q3" value="1" required></td><td class="checkbox"><input type="radio" name="q3" value="2"></td><td class="checkbox"><input type="radio" name="q3" value="3"></td><td class="checkbox"><input type="radio" name="q3" value="4"></td><td>Parece confiante (ou seguro) quando está interagindo com outras pessoas.</td></tr>
                <tr><td>4</td><td class="checkbox"><input type="radio" name="q4" value="1" required></td><td class="checkbox"><input type="radio" name="q4" value="2"></td><td class="checkbox"><input type="radio" name="q4" value="3"></td><td class="checkbox"><input type="radio" name="q4" value="4"></td><td>Quando há sobrecarga de estímulos, apresenta padrões rígidos e inflexíveis de comportamento, aparentemente estranhos.</td></tr>
                <tr><td>5</td><td class="checkbox"><input type="radio" name="q5" value="1" required></td><td class="checkbox"><input type="radio" name="q5" value="2"></td><td class="checkbox"><input type="radio" name="q5" value="3"></td><td class="checkbox"><input type="radio" name="q5" value="4"></td><td>Não percebe quando os outros estão tentando tirar vantagem dele(a).</td></tr>
                <tr><td>6</td><td class="checkbox"><input type="radio" name="q6" value="1" required></td><td class="checkbox"><input type="radio" name="q6" value="2"></td><td class="checkbox"><input type="radio" name="q6" value="3"></td><td class="checkbox"><input type="radio" name="q6" value="4"></td><td>Prefere estar sozinha do que com os outros.</td></tr>
                <tr><td>7</td><td class="checkbox"><input type="radio" name="q7" value="1" required></td><td class="checkbox"><input type="radio" name="q7" value="2"></td><td class="checkbox"><input type="radio" name="q7" value="3"></td><td class="checkbox"><input type="radio" name="q7" value="4"></td><td>Demonstra perceber o que os outros estão pensando ou sentindo.</td></tr>
                <tr><td>8</td><td class="checkbox"><input type="radio" name="q8" value="1" required></td><td class="checkbox"><input type="radio" name="q8" value="2"></td><td class="checkbox"><input type="radio" name="q8" value="3"></td><td class="checkbox"><input type="radio" name="q8" value="4"></td><td>Se comporta de maneira estranha ou bizarra.</td></tr>
                <tr><td>9</td><td class="checkbox"><input type="radio" name="q9" value="1" required></td><td class="checkbox"><input type="radio" name="q9" value="2"></td><td class="checkbox"><input type="radio" name="q9" value="3"></td><td class="checkbox"><input type="radio" name="q9" value="4"></td><td>Precisa da ajuda de outras pessoas para satisfazer suas necessidades básicas.</td></tr>
                <tr><td>10</td><td class="checkbox"><input type="radio" name="q10" value="1" required></td><td class="checkbox"><input type="radio" name="q10" value="2"></td><td class="checkbox"><input type="radio" name="q10" value="3"></td><td class="checkbox"><input type="radio" name="q10" value="4"></td><td>Leva as coisas muito "ao pé da letra" e não compreende o real significado de uma conversa.</td></tr>
                <tr><td>11</td><td class="checkbox"><input type="radio" name="q11" value="1" required></td><td class="checkbox"><input type="radio" name="q11" value="2"></td><td class="checkbox"><input type="radio" name="q11" value="3"></td><td class="checkbox"><input type="radio" name="q11" value="4"></td><td>É autoconfiante.</td></tr>
                <tr><td>12</td><td class="checkbox"><input type="radio" name="q12" value="1" required></td><td class="checkbox"><input type="radio" name="q12" value="2"></td><td class="checkbox"><input type="radio" name="q12" value="3"></td><td class="checkbox"><input type="radio" name="q12" value="4"></td><td>É capaz de comunicar seus sentimentos para as outras pessoas.</td></tr>
                <tr><td>13</td><td class="checkbox"><input type="radio" name="q13" value="1" required></td><td class="checkbox"><input type="radio" name="q13" value="2"></td><td class="checkbox"><input type="radio" name="q13" value="3"></td><td class="checkbox"><input type="radio" name="q13" value="4"></td><td>É estranha na "tomada de vez" das interações com seus colegas (por exemplo, não parece entender a reciprocidade de uma conversa).</td></tr>
                <tr><td>14</td><td class="checkbox"><input type="radio" name="q14" value="1" required></td><td class="checkbox"><input type="radio" name="q14" value="2"></td><td class="checkbox"><input type="radio" name="q14" value="3"></td><td class="checkbox"><input type="radio" name="q14" value="4"></td><td>Não tem boa coordenação.</td></tr>
                <tr><td>15</td><td class="checkbox"><input type="radio" name="q15" value="1" required></td><td class="checkbox"><input type="radio" name="q15" value="2"></td><td class="checkbox"><input type="radio" name="q15" value="3"></td><td class="checkbox"><input type="radio" name="q15" value="4"></td><td>Reconhece e responde de forma apropriada às mudanças no tom de voz e expressões faciais de outras.</td></tr>
                <tr><td>16</td><td class="checkbox"><input type="radio" name="q16" value="1" required></td><td class="checkbox"><input type="radio" name="q16" value="2"></td><td class="checkbox"><input type="radio" name="q16" value="3"></td><td class="checkbox"><input type="radio" name="q16" value="4"></td><td>Evita o contato visual ou tem contato visual diferente.</td></tr>
                <tr><td>17</td><td class="checkbox"><input type="radio" name="q17" value="1" required></td><td class="checkbox"><input type="radio" name="q17" value="2"></td><td class="checkbox"><input type="radio" name="q17" value="3"></td><td class="checkbox"><input type="radio" name="q17" value="4"></td><td>Reconhece quando algo é injusto.</td></tr>
                <tr><td>18</td><td class="checkbox"><input type="radio" name="q18" value="1" required></td><td class="checkbox"><input type="radio" name="q18" value="2"></td><td class="checkbox"><input type="radio" name="q18" value="3"></td><td class="checkbox"><input type="radio" name="q18" value="4"></td><td>Tem dificuldade em fazer amigos, mesmo tentando dar o melhor de si.</td></tr>
                <tr><td>19</td><td class="checkbox"><input type="radio" name="q19" value="1" required></td><td class="checkbox"><input type="radio" name="q19" value="2"></td><td class="checkbox"><input type="radio" name="q19" value="3"></td><td class="checkbox"><input type="radio" name="q19" value="4"></td><td>Fica frustrada tentando expressar suas ideias em uma conversa.</td></tr>
                <tr><td>20</td><td class="checkbox"><input type="radio" name="q20" value="1" required></td><td class="checkbox"><input type="radio" name="q20" value="2"></td><td class="checkbox"><input type="radio" name="q20" value="3"></td><td class="checkbox"><input type="radio" name="q20" value="4"></td><td>Mostra interesses sensoriais incomuns (por exemplo, cheirar seus dedos com frequência) ou estranhos, chacoalhar repetidamente pequenos itens.</td></tr>
                <tr><td>21</td><td class="checkbox"><input type="radio" name="q21" value="1" required></td><td class="checkbox"><input type="radio" name="q21" value="2"></td><td class="checkbox"><input type="radio" name="q21" value="3"></td><td class="checkbox"><input type="radio" name="q21" value="4"></td><td>É capaz de imitar ações e comportamento de outras pessoas quando é socialmente apropriado fazê-lo.</td></tr>
                <tr><td>22</td><td class="checkbox"><input type="radio" name="q22" value="1" required></td><td class="checkbox"><input type="radio" name="q22" value="2"></td><td class="checkbox"><input type="radio" name="q22" value="3"></td><td class="checkbox"><input type="radio" name="q22" value="4"></td><td>Interage apropriadamente com outros adultos.</td></tr>
                <tr><td>23</td><td class="checkbox"><input type="radio" name="q23" value="1" required></td><td class="checkbox"><input type="radio" name="q23" value="2"></td><td class="checkbox"><input type="radio" name="q23" value="3"></td><td class="checkbox"><input type="radio" name="q23" value="4"></td><td>Não participa de atividades em grupo e eventos sociais a menos que seja convidada a fazê-lo.</td></tr>
                <tr><td>24</td><td class="checkbox"><input type="radio" name="q24" value="1" required></td><td class="checkbox"><input type="radio" name="q24" value="2"></td><td class="checkbox"><input type="radio" name="q24" value="3"></td><td class="checkbox"><input type="radio" name="q24" value="4"></td><td>Tem mais dificuldade do que outras pessoas com mudanças em sua rotina.</td></tr>
                <tr><td>25</td><td class="checkbox"><input type="radio" name="q25" value="1" required></td><td class="checkbox"><input type="radio" name="q25" value="2"></td><td class="checkbox"><input type="radio" name="q25" value="3"></td><td class="checkbox"><input type="radio" name="q25" value="4"></td><td>Não parece se importar em estar fora de sintonia ou em um "mundo" diferente dos outros.</td></tr>
                <tr><td>26</td><td class="checkbox"><input type="radio" name="q26" value="1" required></td><td class="checkbox"><input type="radio" name="q26" value="2"></td><td class="checkbox"><input type="radio" name="q26" value="3"></td><td class="checkbox"><input type="radio" name="q26" value="4"></td><td>Oferece conforto a outros quando estão tristes.</td></tr>
                <tr><td>27</td><td class="checkbox"><input type="radio" name="q27" value="1" required></td><td class="checkbox"><input type="radio" name="q27" value="2"></td><td class="checkbox"><input type="radio" name="q27" value="3"></td><td class="checkbox"><input type="radio" name="q27" value="4"></td><td>Evita iniciar interações sociais com outros adultos.</td></tr>
                <tr><td>28</td><td class="checkbox"><input type="radio" name="q28" value="1" required></td><td class="checkbox"><input type="radio" name="q28" value="2"></td><td class="checkbox"><input type="radio" name="q28" value="3"></td><td class="checkbox"><input type="radio" name="q28" value="4"></td><td>Pensa ou fala sobre a mesma coisa repetidamente.</td></tr>
                <tr><td>29</td><td class="checkbox"><input type="radio" name="q29" value="1" required></td><td class="checkbox"><input type="radio" name="q29" value="2"></td><td class="checkbox"><input type="radio" name="q29" value="3"></td><td class="checkbox"><input type="radio" name="q29" value="4"></td><td>É considerada estranha ou esquisita pelas outras pessoas.</td></tr>
                <tr><td>30</td><td class="checkbox"><input type="radio" name="q30" value="1" required></td><td class="checkbox"><input type="radio" name="q30" value="2"></td><td class="checkbox"><input type="radio" name="q30" value="3"></td><td class="checkbox"><input type="radio" name="q30" value="4"></td><td>Fica perturbada em uma situação com muitas coisas acontecendo.</td></tr>
                <tr><td>31</td><td class="checkbox"><input type="radio" name="q31" value="1" required></td><td class="checkbox"><input type="radio" name="q31" value="2"></td><td class="checkbox"><input type="radio" name="q31" value="3"></td><td class="checkbox"><input type="radio" name="q31" value="4"></td><td>Não consegue tirar algo da sua mente uma vez que começa a pensar sobre isso.</td></tr>
                <tr><td>32</td><td class="checkbox"><input type="radio" name="q32" value="1" required></td><td class="checkbox"><input type="radio" name="q32" value="2"></td><td class="checkbox"><input type="radio" name="q32" value="3"></td><td class="checkbox"><input type="radio" name="q32" value="4"></td><td>Tem boa higiene pessoal.</td></tr>
                <tr><td>33</td><td class="checkbox"><input type="radio" name="q33" value="1" required></td><td class="checkbox"><input type="radio" name="q33" value="2"></td><td class="checkbox"><input type="radio" name="q33" value="3"></td><td class="checkbox"><input type="radio" name="q33" value="4"></td><td>É socialmente desajeitada, mesmo quando tenta ser educada.</td></tr>
                <tr><td>34</td><td class="checkbox"><input type="radio" name="q34" value="1" required></td><td class="checkbox"><input type="radio" name="q34" value="2"></td><td class="checkbox"><input type="radio" name="q34" value="3"></td><td class="checkbox"><input type="radio" name="q34" value="4"></td><td>Evita pessoas que querem se aproximar dela por meio de contato afetivo.</td></tr>
                <tr><td>35</td><td class="checkbox"><input type="radio" name="q35" value="1" required></td><td class="checkbox"><input type="radio" name="q35" value="2"></td><td class="checkbox"><input type="radio" name="q35" value="3"></td><td class="checkbox"><input type="radio" name="q35" value="4"></td><td>Tem dificuldade em acompanhar o fluxo de uma conversa normal.</td></tr>
                <tr><td>36</td><td class="checkbox"><input type="radio" name="q36" value="1" required></td><td class="checkbox"><input type="radio" name="q36" value="2"></td><td class="checkbox"><input type="radio" name="q36" value="3"></td><td class="checkbox"><input type="radio" name="q36" value="4"></td><td>Tem dificuldade em se relacionar com familiares.</td></tr>
                <tr><td>37</td><td class="checkbox"><input type="radio" name="q37" value="1" required></td><td class="checkbox"><input type="radio" name="q37" value="2"></td><td class="checkbox"><input type="radio" name="q37" value="3"></td><td class="checkbox"><input type="radio" name="q37" value="4"></td><td>Tem dificuldade em se relacionar com adultos.</td></tr>
                <tr><td>38</td><td class="checkbox"><input type="radio" name="q38" value="1" required></td><td class="checkbox"><input type="radio" name="q38" value="2"></td><td class="checkbox"><input type="radio" name="q38" value="3"></td><td class="checkbox"><input type="radio" name="q38" value="4"></td><td>Responde adequadamente a mudanças de humor dos outros (por exemplo, quando o humor de um amigo muda de feliz para triste).</td></tr>
                <tr><td>39</td><td class="checkbox"><input type="radio" name="q39" value="1" required></td><td class="checkbox"><input type="radio" name="q39" value="2"></td><td class="checkbox"><input type="radio" name="q39" value="3"></td><td class="checkbox"><input type="radio" name="q39" value="4"></td><td>Demonstra interesses extraordinariamente incomuns.</td></tr>
                <tr><td>40</td><td class="checkbox"><input type="radio" name="q40" value="1" required></td><td class="checkbox"><input type="radio" name="q40" value="2"></td><td class="checkbox"><input type="radio" name="q40" value="3"></td><td class="checkbox"><input type="radio" name="q40" value="4"></td><td>É imaginativa sem perder contato com a realidade.</td></tr>
                <tr><td>41</td><td class="checkbox"><input type="radio" name="q41" value="1" required></td><td class="checkbox"><input type="radio" name="q41" value="2"></td><td class="checkbox"><input type="radio" name="q41" value="3"></td><td class="checkbox"><input type="radio" name="q41" value="4"></td><td>Muda de atividade sem motivo aparente.</td></tr>
                <tr><td>42</td><td class="checkbox"><input type="radio" name="q42" value="1" required></td><td class="checkbox"><input type="radio" name="q42" value="2"></td><td class="checkbox"><input type="radio" name="q42" value="3"></td><td class="checkbox"><input type="radio" name="q42" value="4"></td><td>Parece excessivamente sensível a sons, texturas ou cheiros.</td></tr>
                <tr><td>43</td><td class="checkbox"><input type="radio" name="q43" value="1" required></td><td class="checkbox"><input type="radio" name="q43" value="2"></td><td class="checkbox"><input type="radio" name="q43" value="3"></td><td class="checkbox"><input type="radio" name="q43" value="4"></td><td>Gosta de conversar informalmente.</td></tr>
                <tr><td>44</td><td class="checkbox"><input type="radio" name="q44" value="1" required></td><td class="checkbox"><input type="radio" name="q44" value="2"></td><td class="checkbox"><input type="radio" name="q44" value="3"></td><td class="checkbox"><input type="radio" name="q44" value="4"></td><td>Não entende bem relações de causa e efeito, da mesma forma que outros adultos entendem.</td></tr>
                <tr><td>45</td><td class="checkbox"><input type="radio" name="q45" value="1" required></td><td class="checkbox"><input type="radio" name="q45" value="2"></td><td class="checkbox"><input type="radio" name="q45" value="3"></td><td class="checkbox"><input type="radio" name="q45" value="4"></td><td>Geralmente fica interessada no que as pessoas próximas estão prestando atenção.</td></tr>
                <tr><td>46</td><td class="checkbox"><input type="radio" name="q46" value="1" required></td><td class="checkbox"><input type="radio" name="q46" value="2"></td><td class="checkbox"><input type="radio" name="q46" value="3"></td><td class="checkbox"><input type="radio" name="q46" value="4"></td><td>Apresenta expressão facial excessivamente séria.</td></tr>
                <tr><td>47</td><td class="checkbox"><input type="radio" name="q47" value="1" required></td><td class="checkbox"><input type="radio" name="q47" value="2"></td><td class="checkbox"><input type="radio" name="q47" value="3"></td><td class="checkbox"><input type="radio" name="q47" value="4"></td><td>Ri em momentos inapropriados.</td></tr>
                <tr><td>48</td><td class="checkbox"><input type="radio" name="q48" value="1" required></td><td class="checkbox"><input type="radio" name="q48" value="2"></td><td class="checkbox"><input type="radio" name="q48" value="3"></td><td class="checkbox"><input type="radio" name="q48" value="4"></td><td>Tem senso de humor e entende piadas.</td></tr>
                <tr><td>49</td><td class="checkbox"><input type="radio" name="q49" value="1" required></td><td class="checkbox"><input type="radio" name="q49" value="2"></td><td class="checkbox"><input type="radio" name="q49" value="3"></td><td class="checkbox"><input type="radio" name="q49" value="4"></td><td>É extremamente hábil em tarefas intelectuais ou computacionais, mas tem dificuldade com outras atividades práticas.</td></tr>
                <tr><td>50</td><td class="checkbox"><input type="radio" name="q50" value="1" required></td><td class="checkbox"><input type="radio" name="q50" value="2"></td><td class="checkbox"><input type="radio" name="q50" value="3"></td><td class="checkbox"><input type="radio" name="q50" value="4"></td><td>Apresenta comportamentos estranhos e repetitivos.</td></tr>
                <tr><td>51</td><td class="checkbox"><input type="radio" name="q51" value="1" required></td><td class="checkbox"><input type="radio" name="q51" value="2"></td><td class="checkbox"><input type="radio" name="q51" value="3"></td><td class="checkbox"><input type="radio" name="q51" value="4"></td><td>Tem dificuldade em responder diretamente a perguntas, e acaba falando em torno do assunto.</td></tr>
                <tr><td>52</td><td class="checkbox"><input type="radio" name="q52" value="1" required></td><td class="checkbox"><input type="radio" name="q52" value="2"></td><td class="checkbox"><input type="radio" name="q52" value="3"></td><td class="checkbox"><input type="radio" name="q52" value="4"></td><td>Percebe quando está falando muito alto ou fazendo barulho.</td></tr>
                <tr><td>53</td><td class="checkbox"><input type="radio" name="q53" value="1" required></td><td class="checkbox"><input type="radio" name="q53" value="2"></td><td class="checkbox"><input type="radio" name="q53" value="3"></td><td class="checkbox"><input type="radio" name="q53" value="4"></td><td>Fala com tom de voz incomum (robótico, teatral, como se estivesse dando uma palestra, etc.).</td></tr>
                <tr><td>54</td><td class="checkbox"><input type="radio" name="q54" value="1" required></td><td class="checkbox"><input type="radio" name="q54" value="2"></td><td class="checkbox"><input type="radio" name="q54" value="3"></td><td class="checkbox"><input type="radio" name="q54" value="4"></td><td>Age com pessoas como se fossem objetos.</td></tr>
                <tr><td>55</td><td class="checkbox"><input type="radio" name="q55" value="1" required></td><td class="checkbox"><input type="radio" name="q55" value="2"></td><td class="checkbox"><input type="radio" name="q55" value="3"></td><td class="checkbox"><input type="radio" name="q55" value="4"></td><td>Reconhece quando está invadindo o espaço pessoal alheio.</td></tr>
                <tr><td>56</td><td class="checkbox"><input type="radio" name="q56" value="1" required></td><td class="checkbox"><input type="radio" name="q56" value="2"></td><td class="checkbox"><input type="radio" name="q56" value="3"></td><td class="checkbox"><input type="radio" name="q56" value="4"></td><td>Caminha entre pessoas que estão conversando sem perceber.</td></tr>
                <tr><td>57</td><td class="checkbox"><input type="radio" name="q57" value="1" required></td><td class="checkbox"><input type="radio" name="q57" value="2"></td><td class="checkbox"><input type="radio" name="q57" value="3"></td><td class="checkbox"><input type="radio" name="q57" value="4"></td><td>Evita sair de casa, tende a se isolar.</td></tr>
                <tr><td>58</td><td class="checkbox"><input type="radio" name="q58" value="1" required></td><td class="checkbox"><input type="radio" name="q58" value="2"></td><td class="checkbox"><input type="radio" name="q58" value="3"></td><td class="checkbox"><input type="radio" name="q58" value="4"></td><td>Concentra-se em detalhes e perde a visão do todo.</td></tr>
                <tr><td>59</td><td class="checkbox"><input type="radio" name="q59" value="1" required></td><td class="checkbox"><input type="radio" name="q59" value="2"></td><td class="checkbox"><input type="radio" name="q59" value="3"></td><td class="checkbox"><input type="radio" name="q59" value="4"></td><td>É excessivamente desconfiada.</td></tr>
                <tr><td>60</td><td class="checkbox"><input type="radio" name="q60" value="1" required></td><td class="checkbox"><input type="radio" name="q60" value="2"></td><td class="checkbox"><input type="radio" name="q60" value="3"></td><td class="checkbox"><input type="radio" name="q60" value="4"></td><td>É emocionalmente distante, não expressa sentimentos.</td></tr>
                <tr><td>61</td><td class="checkbox"><input type="radio" name="q61" value="1" required></td><td class="checkbox"><input type="radio" name="q61" value="2"></td><td class="checkbox"><input type="radio" name="q61" value="3"></td><td class="checkbox"><input type="radio" name="q61" value="4"></td><td>É inflexível, tem dificuldade para mudar de opinião/ideia.</td></tr>
                <tr><td>62</td><td class="checkbox"><input type="radio" name="q62" value="1" required></td><td class="checkbox"><input type="radio" name="q62" value="2"></td><td class="checkbox"><input type="radio" name="q62" value="3"></td><td class="checkbox"><input type="radio" name="q62" value="4"></td><td>Dá explicações incomuns ou ilógicas para seus comportamentos.</td></tr>
                <tr><td>63</td><td class="checkbox"><input type="radio" name="q63" value="1" required></td><td class="checkbox"><input type="radio" name="q63" value="2"></td><td class="checkbox"><input type="radio" name="q63" value="3"></td><td class="checkbox"><input type="radio" name="q63" value="4"></td><td>Toca ou cumprimenta as pessoas de maneira incomum.</td></tr>
                <tr><td>64</td><td class="checkbox"><input type="radio" name="q64" value="1" required></td><td class="checkbox"><input type="radio" name="q64" value="2"></td><td class="checkbox"><input type="radio" name="q64" value="3"></td><td class="checkbox"><input type="radio" name="q64" value="4"></td><td>Fica muito agitada em situações sociais.</td></tr>
                <tr><td>65</td><td class="checkbox"><input type="radio" name="q65" value="1" required></td><td class="checkbox"><input type="radio" name="q65" value="2"></td><td class="checkbox"><input type="radio" name="q65" value="3"></td><td class="checkbox"><input type="radio" name="q65" value="4"></td><td>Fica com olhar perdido ou olha fixamente para o nada, ou de forma incomum.</td></tr>
            </tbody>
        </table>

        <div class="button-container">
            <button type="submit">Enviar Formulário</button>
            <button type="button" onclick="window.print()">Imprimir</button>
            <button type="button" class="whatsapp-share" onclick="shareWhatsApp()">Compartilhar via WhatsApp</button>
        </div>
    </form>

    <div class="footer">
        <p>Nota: Este questionário é destinado exclusivamente a uso profissional por psicólogos habilitados.</p>
        <p>Desenvolvido para avaliação neuropsicológica. Não reproduzir sem autorização.</p>
    </div>

    <script>
        function shareWhatsApp() {
            const url = window.location.href;
            const text = "Confira o Questionário Neuropsicológico – Heterorrelato (Adulto): " + url;
            window.open(`https://wa.me/?text=${encodeURIComponent(text)}`, '_blank');
        }
    </script>
</body>
</html>

