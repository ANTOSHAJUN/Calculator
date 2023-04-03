*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
    outline: none;
}
p{
    background-color: #ffffff;
    font-size: 30px;
    padding: 10px;
}
.container{
    height: 100vh;
    display: flex;
    justify-content: center;
    background-color: rgb(245, 111, 151);
    align-items: center;

}
.calculator{
    background-color: #ffffff;
    padding: 15px;
    border-radius: 30px;
    box-shadow: inset 5px 5px 12px #ffffff,
                      5px 5px 12px rgba(0,0,0,.16);
    display: grid;
    grid-template-columns: repeat(4,70px);

}

input{
    grid-column: span 4;
    height: 70px;
    width: 260px;
    background-color: #ffffff;
    box-shadow: inset -5px -5px 12px #ffffff,
                inset 5px 5px 12px rgba(0,0,0,.16);
    border: none;
    border-radius: 30px;
    color: rgb(70, 70,70);
    font-size: 20px;
    text-align: end;
    margin: auto;
    margin-top: 40px;
    margin-bottom: 30px;
    padding: 20px;
}
button{
    height: 48px;
    width: 48px;
    background-color: #ffffff;
    box-shadow: inset -5px -5px 12px #ffffff,
                inset 5px 5px 12px rgba(0,0,0,.16);
    border: none;
    border-radius: 50%;
    margin: 8px;
    font-size: 16px;
    
}

.equal{
    width: 115px;
    border-radius: 40px;
}
