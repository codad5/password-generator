<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Password Generator</title>
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }

        body{
            width:100vw;
            overflow-x: hidden;
        }

        main{
            background: #555;
            width:100vw;
            height:90vh;
            display: grid;
            place-items: center;

        }

        form{
            width: 350px;
            border: 2px solid #ffd207;
            text-align: center;
            padding:15px;
        }
        form .password_box{
            width:100%;
            height:40px;
            background:transparent;
            border: none;
            border: solid 2px #ffd207;
            outline: none;
            display:flex;
            /* box-shadow:inset 0 .5rem 1rem rgba(0,0,0,.15)!important; */
        }

        .password_box input[type="text"]{
            flex-basis: 70%;
            background:transparent;
            border: none;
            outline: none;
            padding:0px 6px;
            color:whitesmoke;

        }
        .password_box #genPasswordBtn{
            flex-basis: 30%;
            background:#ffd207;
            border: none;
            outline: none;
            

        }

        .password_lenght{
            width:100%;
            height:20px;
            padding:15px 5px;
            display:grid;
            place-items: center;
        }

        .password_lenght input[type="range"]{
            width:90%;

        }
        .show_lenght{
            color:#ffd207;
        }
        .includes{
            width: 100%;
            height: 250px;

            display:grid;
            grid-template-columns: repeat(2, 50%);
            grid-template-rows: repeat(2, 50%);
            padding:10px;
        }

        .include_box{
            width:100%;
            height:100%;
            display: flex;
            flex-direction: row-reverse;
            align-items: center;


        }

        .include_box input{
            height:20px;
            flex-basis: 30%;
            
        }
        .include_box label{
            height:100%;
            flex-basis: 70%;
            display: grid;
            place-items: center;
            color:antiquewhite;
            font-size: 0.8rem;
            text-align:left;
        }

        .copy_panel{
            width:100%;
            height:40px;
            text-align: center;
        }
        .copy_pwd{

            width:40%;
            background:#ffd207;
            border: none;
            outline: none;
            height:100%;

        }
        footer{
            width:100vw;
            height:200px;
            background:#111;
            position:relative;
        }

        .footer_after{
            content: "?";
            position:absolute;
            top:-30px;
            width:60px;
            height:60px;
            background:#ffd207;
            display:grid;
            place-items: center;
            color:#fff;
            font-size: 2rem;
            left:50px;
            transform: rotateZ(45deg);
            
        }
        
        .footer_after_text{
            
            transform: rotateZ(-45deg);
        }

        .footer_header{
            width:100%;
            height:50px;
            padding: 0 20%;
            color:#ffd207;
            
        }

        .footer_header_text{
            height:100%;
            display: grid;
            place-items: center;
            font-size:2rem;
            justify-content: center;
            align-items: center;
        }

        .footer_header_text sub,.footer_header_text sup{
            height: 80%;
            flex-basis:20px;
            display:inline-block;
        }
        .footer_header_text sub{
            display:inline-flex;
            align-items:flex-end;
            font-size:0.8rem;
        }

        .notification{
            padding:15px 20px;
            background: #ccc;
            position: fixed;
            top:20px;
            left:20px;
            color:white;
            z-index:10;
            border-radius: 10px;
            visibility:hidden;

        }

        .alert-danger{
            color:red;
        }
        .alert-warn{
            background:#add489;
        }
    </style>
</head>
<body>
    <main>
        <div class="notification">
            Copied
        </div>
       <div class="formwrapper">
           <form action="" method="get">
               <div class="password_box">

                   <input type="text" name="" id="password_box" placeholder="Generated Password" readonly>
                   <button id="genPasswordBtn">
                       Generate
                   </button>
               </div>
               <div class="password_lenght">
                   <input type="range" name="" id="passwordLenght" min="3" max="40" minlength="10" value="8">
                   <div class="show_lenght">
                       8
                   </div>
               </div>

               <div class="includes">
                   <div class="include_box">
                       <label for="">Include Cap Letters</label>
                       <input type="checkbox" name="" id="cap_letter">
                   </div>
                   <div class="include_box">
                       <label for="">Include Small Letters</label>
                       <input type="checkbox" name="" id="small_letter">
                   </div>
                   <div class="include_box">
                       <label for="">Include Numbers</label>
                       <input type="checkbox" name="" id="number">
                   </div>
                   <div class="include_box">
                       <label for="">Include Symbols</label>
                       <input type="checkbox" name="" id="symbols">
                   </div>
                   

               </div>

               <div class="copy_panel">
                   <button class="copy_pwd">
                       COPY
                   </button>

               </div>

           </form>
       </div>

    </main>
    <footer>
        <div class="footer_header">
                <h2 class="footer_header_text">PASSWORD GENERATOR</h2>
            </div>
        <div class="footer_header "  >
                <h3 class="footer_header_text" style='font-size:1.2rem;display:flex;'> <sub>By</sub> &nbsp;  ANIEZEOFOR CHIBUEZE MICHAEL &nbsp;<sup> Codad5</sup></h2>
            </div>
        <div class="footer_after">
            

            <span class="footer_after_text">
                ?
            </span>
        </div>

    </footer>
    
</body>
<script>
    const VERSION = '1.0',
    passwordInput = document.querySelector('#password_box'),
    generateBtn = document.querySelector('#genPasswordBtn') ,
    copy = document.querySelector('.copy_pwd'),
    capLetter = document.querySelector('#cap_letter'),
    numberInput = document.querySelector('#number'),
    symbolsInput = document.querySelector('#symbols'),
    smallLetter = document.querySelector('#small_letter'),
    passwordLenght = document.querySelector('#passwordLenght'),
    notibar = document.querySelector('.notification'),
    genPassword = (selections, lenght) => {
        let password = "";
            for (let index = 0; index < lenght; index++) {
              password+=selections[Math.floor(Math.random() * selections.length)];

                
            }
            return password;
    },
    pushNoti = (noti, type='alert') => {
        notibar.innerText = noti;
        notibar.style.visibility = 'visible';
        notibar.classList.add(type);

        setTimeout(() => {
            notibar.style.visibility = 'hidden';
            notibar.classList.remove(type);
        }, 3500);
    };
    document.querySelector('form').addEventListener('submit', (event) => {
        event.preventDefault();
    })
    copy.addEventListener('click', (event) => {
        if(passwordInput.value.length > 0){

            navigator.clipboard.writeText(passwordInput.value);
            // prompt('copied');
            pushNoti('Copied!')
        }else{
            pushNoti('Nothing to Copy', 'alert-warn')

        }
    })

    passwordLenght.addEventListener('input', (event) => {
        const showLenght = document.querySelector('.show_lenght');
        if(passwordLenght.value < 8){
            showLenght.style.color="red";
        }
        else{
            showLenght.style.color="#ffd207";

        }
        showLenght.innerText = passwordLenght.value;
        
    })

    generateBtn.addEventListener('click', (event) => {
        const capAlphabet = 'ABCDEFGHIJKLMNOPQRSTUVWSYZ';
        const Number = '1234567890',
        symbols = '$_-%&@#?',
        smallAlphabet = 'abcdefghijklmnopqrstuvwsxyz';
        let selection = '';
        if(smallLetter.checked){
            selection+=smallAlphabet;
        }
        if(capLetter.checked){
            selection+=capAlphabet;
        }
        if(numberInput.checked){
            selection+=Number;
        }
        if(symbolsInput.checked){
            selection+=symbols;
        }
        if(selection.length > 0){
            
            passwordInput.value = genPassword(selection, passwordLenght.value);
            pushNoti('Generated')
        }
        
    })

    
</script>
</html>