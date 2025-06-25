# Calculator.css
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #5f73b3;
}
.text{
    margin-left:35px;

}

.calculator {
    border: 1px solid #ccc;
    padding: 20px;
    border-radius: 10px;
    background-color: white;
    box-shadow: 0 5px 10px rgba(0,0,0,0.2);
}

.display input {
    width: 100%;
    height: 50px;
    font-size: 24px;
    text-align: right;
    border: none;
    outline: none;
    padding: 10px;
    box-sizing: border-box;
    background-color: rgb(191, 190, 190);
}

.buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-gap: 10px;
    margin-top: 20px;
}

button {
    padding: 20px;
    font-size: 18px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    background-color: #eee;
    transition: background-color 0.2s;
}

button:hover {
    background-color: #ddd;
}

button:nth-child(4n) {
    background-color: #ff7043;
    color: white;
}

button:nth-child(4n):hover {
    background-color: #ff5722;
}
