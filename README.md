# Janaína Pereira de Jesus <!-- NOME EM NEGRITO AQUI -->
Psicóloga Clínica e Terapeuta Cognitivo-Comportamental <!-- PODE EDITAR ESSA PARTE TAMBÉM -->


<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Janaína Pereira | Psicóloga</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f0f4f8;
            color: #333;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            width: 100%;
            max-width: 600px;
            background: #ffffff;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
        }

        .profile-header {
            text-align: center;
            margin-bottom: 20px;
        }

        .profile-header h1 {
            color: #007bff;
            font-weight: 700;
            margin-bottom: 5px;
        }

        .profile-header p {
            color: #6c757d;
            font-weight: 400;
            margin-top: 0;
        }

        .form-section {
            padding: 20px;
            background-color: #eef5ff;
            border-radius: 10px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            font-weight: 600;
            margin-bottom: 8px;
            color: #495057;
        }

        .form-group input, .form-group select, .form-group textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ced4da;
            border-radius: 8px;
            box-sizing: border-box;
            font-size: 1em;
            transition: border-color 0.3s ease;
        }

        .form-group textarea {
            resize: none;
            height: 100px;
            max-length: 180;
        }

        .whatsapp-button {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            padding: 15px;
            background-color: #25D366;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 1.1em;
            font-weight: 600;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s ease;
            margin-top: 25px;
        }

        .whatsapp-button:hover {
            background-color: #128C7E;
        }

        .whatsapp-button img {
            width: 24px;
            height: 24px;
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-header">
            <h1>Janaína Pereira de Jesus</h1> <!-- NOME PRINCIPAL AQUI -->

            <!DOCTYPE html> <!-- INICIO DO CODIGO DO SIMBOLO -->
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Símbolo Psicologia Brilhante</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f0f4f8; /* Fundo suave */
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            overflow: hidden; /* Para garantir que o brilho não cause scroll */
        }

        .symbol-container {
            position: relative;
            width: 300px; /* Tamanho do contêiner */
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .psychology-symbol {
            font-size: 150px; /* Tamanho do símbolo */
            font-weight: 700;
            color: #007bff; /* Cor base do símbolo: Azul claro */
            text-shadow: 0 0 10px rgba(0, 123, 255, 0.6), 
                         0 0 20px rgba(0, 123, 255, 0.4), 
                         0 0 30px rgba(0, 123, 255, 0.2);
            transition: text-shadow 0.3s ease-in-out;
            cursor: pointer; /* Indica que é interativo */
            animation: glow-animation 2s infinite alternate; /* Animação de brilho */
        }

        @keyframes glow-animation {
            from {
                text-shadow: 0 0 5px #007bff,
                             0 0 10px #007bff,
                             0 0 15px #007bff,
                             0 0 20px #007bff;
            }
            to {
                text-shadow: 0 0 10px #007bff,
                             0 0 20px #007bff,
                             0 0 30px #007bff,
                             0 0 40px #007bff,
                             0 0 50px #007bff;
            }
        }

        .psychology-symbol:hover {
            text-shadow: 0 0 15px #007bff, 
                         0 0 30px #007bff, 
                         0 0 45px #007bff,
                         0 0 60px #007bff; /* Efeito mais intenso ao passar o mouse */
        }

        .text-around {
            position: absolute;
            width: 100%;
            height: 100%;
            /* Ajuste para alinhar o texto ao redor */
            display: flex;
            justify-content: center;
            align-items: center;
            pointer-events: none; /* Permite clicar no símbolo através do texto */
        }

        .text-around span {
            position: absolute;
            color: #6c757d; /* Cor do texto */
            font-size: 1.2em;
            font-weight: 500;
            white-space: nowrap; /* Impede que o texto quebre */
            transform-origin: 0 150px; /* Ponto central da rotação (metade da largura/altura do container) */
            /* Ajuste fino para posicionamento */
        }
    </style>
</head>
<body>
    <div class="symbol-container">
        <div id="psi-symbol" class="psychology-symbol">
            &#936; </div>
        <div class="text-around">
            <span id="text-span">Psicóloga Janaína Pereira de Jesus</span>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const textSpan = document.getElementById('text-span');
            const text = textSpan.textContent;
            textSpan.textContent = ''; // Limpa o texto original

            const radius = 120; // Raio para posicionar as letras (ajuste conforme o tamanho do seu símbolo)
            const angleIncrement = (360 / text.length); // Ângulo para cada letra

            // Adiciona cada letra individualmente para girá-las
            for (let i = 0; i < text.length; i++) {
                const charSpan = document.createElement('span');
                charSpan.textContent = text[i];
                charSpan.style.position = 'absolute';
                charSpan.style.transformOrigin = '0 120px'; // Ajuste o '120px' para o raio do círculo
                charSpan.style.transform = `rotate(${i * angleIncrement - 90}deg) translate(${radius}px) rotate(90deg)`;
                
                // Ajuste fino para espaçamento entre as letras se necessário
                // charSpan.style.left = `${(i * 10)}px`; 

                textSpan.appendChild(charSpan);
            }
        });

        // Opcional: Adicionar um efeito de brilho mais dinâmico com JavaScript
        // (neste caso, o CSS já faz um bom trabalho com a animação de glow)
        // Se quisesse um brilho diferente ao clicar, poderia adicionar aqui.
    </script>
</body>
</html> <!--FINAL DO CODIGO DO SIMBOLO -->


            
            <p>Psicóloga Clínica e Terapeuta Cognitivo-Comportamental</p> <!--TENTAR ANEXAR LOGO MARCA AQUI -->
        </div>

        <div class="form-section">
            <p style="text-align: center; font-size: 1.1em; font-weight: 600;">Para agendar uma sessão, preencha o formulário abaixo:</p>

            <form id="contact-form">
                <div class="form-group">
                    <label for="encontrou">Como encontrou meu perfil?</label>
                    <select id="encontrou" required>
                        <option value="">Selecione uma opção</option>
                        <option value="Instagram">Instagram</option>
                        <option value="Facebook">Facebook</option>
                        <option value="Amigo">Indicação de amigo(a)</option>
                        <option value="BuscaOnline">Busca online (Google, etc.)</option>
                        <option value="Outro">Outro</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="nome">Qual seu nome?</label>
                    <input type="text" id="nome" required>
                </div>

                <div class="form-group">
                    <label for="idade">Quantos anos você tem?</label>
                    <input type="number" id="idade" required>
                </div>

                <div class="form-group">
                    <label for="acompanhamento">Já fez algum acompanhamento psicológico?</label>
                    <select id="acompanhamento" required>
                        <option value="Sim">Sim</option>
                        <option value="Nao">Não</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="medicacao">Faz uso de alguma medicação?</label>
                    <select id="medicacao" required>
                        <option value="Sim">Sim</option>
                        <option value="Nao">Não</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="horario">Qual dia e horário você tem interesse em ser atendido(a)?</label>
                    <textarea id="horario" maxlength="180" placeholder="Ex: Terça-feira, 19:00 ou Sábados pela manhã"></textarea>
                </div>
            </form>

            <a href="#" id="whatsapp-link" class="whatsapp-button" onclick="generateLink()">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp Logo">
                Enviar Mensagem para Agendamento
            </a>
        </div>
    </div>

    <script>
        function generateLink() {
            const encontrou = document.getElementById('encontrou').value;
            const nome = document.getElementById('nome').value;
            const idade = document.getElementById('idade').value;
            const acompanhamento = document.getElementById('acompanhamento').value;
            const medicacao = document.getElementById('medicacao').value;
            const horario = document.getElementById('horario').value;
            const whatsappLink = document.getElementById('whatsapp-link');

            if (!encontrou || !nome || !idade) {
                alert("Por favor, preencha todos os campos obrigatórios (marcados com *).");
                return;
            }

            let message = `Olá, Janaína! Encontrei seu perfil via ${encontrou}.`;
            message += `\nMeu nome é ${nome} e tenho ${idade} anos.`;
            message += `\nJá fiz acompanhamento psicológico: ${acompanhamento}.`;
            message += `\nFaço uso de medicação: ${medicacao}.`;
            
            if (horario) {
                message += `\n\nTenho interesse em ser atendido(a) no seguinte dia/horário: ${horario}.`;
            } else {
                message += `\n\nNão especifiquei um horário, mas gostaria de agendar um atendimento.`;
            }

            const encodedMessage = encodeURIComponent(message);
            const whatsappUrl = `https://wa.me/5531986015600?text=${encodedMessage}`;
            
            whatsappLink.href = whatsappUrl;
            whatsappLink.target = "_blank";
        }
    </script>
</body>
</html>
