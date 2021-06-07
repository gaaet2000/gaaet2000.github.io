<head>
 h1
 {
 text_align : center ;
 }
 </head>

<h1>MOT DE PASSE</h1>

<span>Veuillez saisir le mot de passe : </span>
<input type='password' id='password'>
<button id='ok'>Confirmer</button>
<span id='error'></span>
 
<script>
 
document.getElementById('ok').addEventListener('click',function(){
    if(document.getElementById('password').value=='azerty'){
        location.href='https://gaaet2000.github.io/bureau';
    }
    else{
        document.getElementById('error').innerHTML='Le mot de pass est incorrect';
    }
},false);

</script>
