<link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css'><div class="container">
	<div class="glow">
		<div class="text-container">
			<span class="text"> Skorpion</span>
			<br>
			<span class="text"> By Bmw-x6</span>
			<br>
			<div class="playback_controls">
				<button onclick="skip('back')"><i class="fa fa-fast-backward"></i></button>
				<button onclick="playpause()"><i class="fa fa-play"></i><i class="fa fa-pause"></i></button>
				<button onclick="stop()"><i class="fa fa-stop"></i></button>
				<button onclick="skip('fwd')"><i class="fa fa-fast-forward"></i></button>
			</div>
			<br>
			<div id="seekbar">
				<input type="range" oninput="setPos(this.value)" id="seek" value="0" max="">
			</div>
			<br>
			<div class="volume_controls">
				<button id="mute" onclick="mute()"><i class="fa fa-volume-up"></i></button>
				<input type="range" id="volume" oninput="setVolume(this.value)" min="0" max="1" step="0.01" value="1">
			</div>
		</div>
	</div>
</div>
