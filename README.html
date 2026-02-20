<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Samar 💚</title>

<style>
body{
  margin:0;
  overflow:hidden;
  background: linear-gradient(to bottom, #0f2027, #203a43, #2c5364);
  font-family: 'Segoe UI', sans-serif;
  text-align:center;
  color:white;
}

/* Cake */
.cake-container{
  position:absolute;
  top:50%;
  left:50%;
  transform:translate(-50%,-50%);
  z-index:10;
}

.cake{
  width:200px;
  height:120px;
  background:#2ecc71;
  border-radius:10px;
  position:relative;
  box-shadow:0 0 20px #2ecc71;
}

.candle{
  width:10px;
  height:40px;
  background:white;
  position:absolute;
  top:-40px;
  left:95px;
}

.flame{
  width:15px;
  height:15px;
  background:orange;
  border-radius:50%;
  position:absolute;
  top:-15px;
  left:-2.5px;
  animation:flicker 0.2s infinite alternate;
}

@keyframes flicker{
  from{transform:scale(1);}
  to{transform:scale(1.2);}
}

.message{
  position:absolute;
  bottom:15%;
  width:100%;
  font-size:28px;
  opacity:0;
  transition:1s;
}

/* Petals */
.petal{
  position:absolute;
  top:-10px;
  font-size:20px;
  animation:fall linear infinite;
}

@keyframes fall{
  to{
    transform:translateY(110vh) rotate(360deg);
  }
}
</style>
</head>

<body>

<div class="cake-container">
  <div class="cake"></div>
  <div class="candle">
    <div class="flame" id="flame"></div>
  </div>
</div>

<div class="message" id="message">
  🌸 Happy Birthday Samar 💚 <br>
  Stay as beautiful as your soul ✨
</div>

<script>
// 🌸 Create Falling Petals
function createPetal(){
  const petal = document.createElement("div");
  petal.classList.add("petal");
  petal.innerHTML = "🌸";
  petal.style.left = Math.random()*100 + "vw";
  petal.style.animationDuration = (5+Math.random()*5) + "s";
  document.body.appendChild(petal);
  setTimeout(()=>{petal.remove();},10000);
}
setInterval(createPetal,300);

// ✋ Interactive touch move
document.addEventListener("touchmove", function(e){
  let touch = e.touches[0];
  let spark = document.createElement("div");
  spark.innerHTML="✨";
  spark.style.position="absolute";
  spark.style.left=touch.clientX+"px";
  spark.style.top=touch.clientY+"px";
  spark.style.fontSize="20px";
  document.body.appendChild(spark);
  setTimeout(()=>spark.remove(),500);
});

// 🎤 Microphone blow detection
navigator.mediaDevices.getUserMedia({ audio: true })
.then(stream=>{
  const audioContext = new (window.AudioContext || window.webkitAudioContext)();
  const mic = audioContext.createMediaStreamSource(stream);
  const analyser = audioContext.createAnalyser();
  mic.connect(analyser);
  const data = new Uint8Array(analyser.frequencyBinCount);

  function detectBlow(){
    analyser.getByteFrequencyData(data);
    let volume = data.reduce((a,b)=>a+b)/data.length;

    if(volume > 60){ // Blow threshold
      document.getElementById("flame").style.display="none";
      document.getElementById("message").style.opacity=1;
    }
    requestAnimationFrame(detectBlow);
  }
  detectBlow();
})
.catch(()=>alert("Please allow microphone access to blow the candle 🎤"));

</script>

</body>
</html># ss
