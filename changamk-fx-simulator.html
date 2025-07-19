<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Changamka FX USSD Simulator</title>
    <style>
        :root {
            --jambo-orange: #FF6B00;
            --equity-blue: #003A70;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
        }
        .phone-mockup {
            width: 320px;
            background: #111;
            border-radius: 30px;
            padding: 20px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.25);
            position: relative;
            border: 3px solid var(--jambo-orange);
        }
        .screen {
            background: #000;
            color: #fff;
            height: 500px;
            border-radius: 15px;
            padding: 15px;
            font-family: monospace;
            overflow-y: auto;
        }
        .ussd-header {
            color: var(--jambo-orange);
            font-weight: bold;
            text-align: center;
            margin-bottom: 20px;
            font-size: 1.2em;
        }
        .message {
            margin: 10px 0;
            line-height: 1.5;
        }
        .system-msg {
            color: #00C1D4;
        }
        .user-msg {
            color: var(--jambo-orange);
            text-align: right;
        }
        .input-area {
            display: flex;
            margin-top: 20px;
        }
        #ussd-input {
            flex: 1;
            background: #222;
            color: white;
            border: 1px solid #444;
            padding: 10px;
            font-size: 1.2em;
            border-radius: 5px 0 0 5px;
        }
        #send-btn {
            background: var(--jambo-orange);
            color: white;
            border: none;
            padding: 0 20px;
            border-radius: 0 5px 5px 0;
            cursor: pointer;
            font-weight: bold;
        }
        .keypad {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            margin-top: 20px;
        }
        .key {
            background: #333;
            color: white;
            border: none;
            border-radius: 50%;
            height: 60px;
            font-size: 1.5em;
            cursor: pointer;
            transition: all 0.2s;
        }
        .key:hover {
            background: #444;
        }
        .key:active {
            transform: scale(0.95);
            background: var(--jambo-orange);
        }
        .dial-btn {
            grid-column: span 3;
            background: var(--jambo-orange);
            border-radius: 30px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="phone-mockup">
        <div class="screen" id="ussd-screen">
            <div class="ussd-header">Changamka FX</div>
            <div class="message system-msg">Welcome to Changamka FX Simulator</div>
            <div class="message system-msg">Dial *483*7# to start</div>
            <div id="conversation"></div>
        </div>
        
        <div class="input-area">
            <input type="text" id="ussd-input" placeholder="Enter USSD code" value="*483*7#">
            <button id="send-btn">OK</button>
        </div>
        
        <div class="keypad">
            <button class="key" data-key="1">1</button>
            <button class="key" data-key="2">2</button>
            <button class="key" data-key="3">3</button>
            <button class="key" data-key="4">4</button>
            <button class="key" data-key="5">5</button>
            <button class="key" data-key="6">6</button>
            <button class="key" data-key="7">7</button>
            <button class="key" data-key="8">8</button>
            <button class="key" data-key="9">9</button>
            <button class="key" data-key="*">*</button>
            <button class="key" data-key="0">0</button>
            <button class="key" data-key="#">#</button>
            <button class="key dial-btn" id="dial-btn">Dial</button>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const conversation = document.getElementById('conversation');
            const ussdInput = document.getElementById('ussd-input');
            const sendBtn = document.getElementById('send-btn');
            const dialBtn = document.getElementById('dial-btn');
            const keys = document.querySelectorAll('.key[data-key]');
            
            // Add user input to conversation
            function addMessage(text, isUser = false) {
                const msgDiv = document.createElement('div');
                msgDiv.className = isUser ? 'message user-msg' : 'message system-msg';
                msgDiv.textContent = text;
                conversation.appendChild(msgDiv);
                conversation.scrollTop = conversation.scrollHeight;
            }
            
            // Process USSD commands
            function processUSSD(code) {
                addMessage(code, true);
                
                if (code === '*483*7#') {
                    setTimeout(() => {
                        addMessage("Changamka FX Menu:");
                        addMessage("1. Join Forex Pool");
                        addMessage("2. Check Pool Rates");
                        addMessage("3. Agent Dashboard");
                        addMessage("00. Exit");
                    }, 500);
                } 
                else if (code === '1') {
                    setTimeout(() => {
                        addMessage("Enter pool amount (KES):");
                    }, 500);
                }
                else if (code === '10000') {
                    setTimeout(() => {
                        addMessage("Pool joined successfully!");
                        addMessage("Current pool rate: 1 USD = KES 158.50");
                        addMessage("Bank rate: KES 153.20");
                        addMessage("You save: KES 530");
                        addMessage("00. Main Menu");
                    }, 500);
                }
                else if (code === '3') {
                    setTimeout(() => {
                        addMessage("AGENT DASHBOARD");
                        addMessage("Active pools: 12");
                        addMessage("Total volume: KES 8.4M");
                        addMessage("Your earnings: KES 33,600");
                        addMessage("00. Main Menu");
                    }, 500);
                }
                else {
                    setTimeout(() => {
                        addMessage("Invalid selection. Try again");
                    }, 500);
                }
                
                ussdInput.value = '';
            }
            
            // Event listeners
            sendBtn.addEventListener('click', () => {
                if (ussdInput.value) {
                    processUSSD(ussdInput.value);
                }
            });
            
            dialBtn.addEventListener('click', () => {
                if (ussdInput.value) {
                    processUSSD(ussdInput.value);
                }
            });
            
            keys.forEach(key => {
                key.addEventListener('click', () => {
                    ussdInput.value += key.getAttribute('data-key');
                });
            });
            
            ussdInput.addEventListener('keypress', (e) => {
                if (e.key === 'Enter') {
                    processUSSD(ussdInput.value);
                }
            });
        });
    </script>
</body>
</html>