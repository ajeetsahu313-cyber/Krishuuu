# Krishuuu<!DOCTYPE html><html>
<head>
<meta charset="UTF-8">
<title>Krishuu ❤️</title><style>
body {
    margin:0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg,#ff9a9e,#fecfef);
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
}

.card{
    background:white;
    padding:40px;
    border-radius:20px;
    box-shadow:0 10px 40px rgba(0,0,0,0.3);
    text-align:center;
}

h1{
    color:#ff1744;
}

button{
    padding:15px 40px;
    font-size:18px;
    border:none;
    border-radius:40px;
    cursor:pointer;
    margin:10px;
}

#yesBtn{
    background:#ff1744;
    color:white;
}

#noBtn{
    background:#ccc;
    position:relative;
}
</style></head><body><div class="card">
<h1>Will You Be My Girlfriend? ❤️</h1><button id="yesBtn" onclick="yes()">Yes 😍</button>
<button id="noBtn" onmouseover="run()">No 😢</button>

</div><script>
function yes(){
    document.body.innerHTML="<h1 style='text-align:center;margin-top:40vh;'>I Love You ❤️</h1>";
}

function run(){
    let btn=document.getElementById("noBtn");
    btn.style.position="absolute";
    btn.style.left=Math.random()*80+"%";
    btn.style.top=Math.random()*80+"%";
}
</script></body>
</html>
