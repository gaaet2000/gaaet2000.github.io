<h1>MOT DE PASSE</h1>

<form>
  <div>
    <label for="pass">Veuillez saisir le mot de passe : </label>
    <input type="password" id="pass" pattern="ght4">
    <span class="validity"></span>
  </div>
  <div>
    <button>Confirmer</button>
    <a href="http://exemple.com"></a>
  </div>
</form>

<span>Entrez le mot de pass: </span><input type='password' id='password'>
<button id='ok'>Ok</button>
<span id='error'></span>
 
<script>
document.getElementById('ok').addEventListener('click',function(){
    if(document.getElementById('password').value=='azerty'){
        location.href='http://google.fr';
    }
    else{
        document.getElementById('error').innerHTML='Le mot de pass est incorecte';
    }
},false);
 
 
 
</script>
