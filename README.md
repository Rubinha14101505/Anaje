# Pousada Quinta Do Ypuã
## CSS RESERVA 
/* Estilo geral */
body {
    font-family: 'Roboto', Arial, sans-serif;
    background: linear-gradient(135deg, #1a1a2e, #16213e);
    color: #ffffff;
    margin: 0;
    padding: 0;
}

/* Header */
header {
    text-align: center;
    padding: 20px;
    background: linear-gradient(90deg, #0f3460, #53354a);
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.5);
}

header h1 {
    font-size: 2.5rem;
    margin: 0;
    color: #e94560;
}

header p {
    font-size: 1.2rem;
    color: #d1d1e9;
}

.logout-button {
    background-color: #e94560;
    border: none;
    color: white;
    padding: 10px 20px;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s ease;
    position: absolute;
    top: 20px;
    right: 20px;
}

.logout-button:hover {
    background-color: #f77f98;
}

/* Menu Container */
.menu-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

/* Menu Option */
.menu-option {
    background: rgba(255, 255, 255, 0.1);
    border-radius: 10px;
    padding: 20px;
    max-width: 300px;
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.menu-option:hover {
    transform: scale(1.05);
    box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
}

.menu-option h2 {
    font-size: 1.5rem;
    color: #00adb5;
    margin-bottom: 10px;
}

.menu-option p {
    font-size: 1rem;
    color: #d1d1e9;
    margin-bottom: 20px;
}

.menu-button {
    display: inline-block;
    background: linear-gradient(45deg, #00adb5, #393e46);
    color: white;
    text-decoration: none;
    padding: 10px 20px;
    border-radius: 5px;
    font-weight: bold;
    transition: background 0.3s ease;
}

.menu-button:hover {
    background: linear-gradient(45deg, #66fcf1, #45a29e);
}

/* Chatbot Button */
#chatbotButton {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-color: #393e46;
    border: none;
    color: white;
    font-size: 1rem;
    padding: 15px 20px;
    border-radius: 50%;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.5);
    cursor: pointer;
    transition: transform 0.3s ease, background-color 0.3s ease;
}

#chatbotButton:hover {
    transform: scale(1.1);
    background-color: #00adb5;
}

/* Chatbot Window */
#chatbotWindow {
    display: none;
    position: fixed;
    bottom: 100px;
    right: 20px;
    background: rgba(0, 0, 0, 0.8);
    border-radius: 10px;
    width: 300px;
    box-shadow: 0 8px 15px rgba(0, 0, 0, 0.5);
    overflow: hidden;
    flex-direction: column;
}

#chatbotHeader {
    background: linear-gradient(45deg, #00adb5, #393e46);
    color: white;
    padding: 10px;
    font-size: 1.2rem;
    font-weight: bold;
    text-align: center;
    border-bottom: 1px solid rgba(255, 255, 255, 0.2);
}

#chatbotContent {
    flex-grow: 1;
    padding: 10px;
    overflow-y: auto;
    color: #d1d1e9;
    font-size: 0.9rem;
}

#chatbotContent .message {
    margin-bottom: 10px;
    padding: 10px;
    border-radius: 5px;
}

#chatbotContent .bot-message {
    background: #00adb5;
    color: #ffffff;
    align-self: flex-start;
}

#chatbotContent .user-message {
    background: #393e46;
    color: #ffffff;
    align-self: flex-end;
}

#chatbotInputContainer {
    display: flex;
    padding: 10px;
    background: rgba(255, 255, 255, 0.1);
}

#chatbotInput {
    flex-grow: 1;
    padding: 10px;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
    margin-right: 10px;
    background: rgba(255, 255, 255, 0.1);
    color: white;
}

#chatbotInput:focus {
    outline: none;
    background: rgba(255, 255, 255, 0.2);
}

#sendButton {
    background: #00adb5;
    border: none;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s ease;
}

#sendButton:hover {
    background: #66fcf1;
}
