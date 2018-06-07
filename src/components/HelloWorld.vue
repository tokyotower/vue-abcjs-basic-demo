<template>
	<div class="hello">
		<div id="paper"></div>
	</div>
</template>

<script>
import abcjs from "abcjs";

export default {
  mounted: function() {
    abcjs.renderAbc("paper", this.tune, {});
  },
  name: "hello",
  data() {
    return {
      tune:
        'X:1\nT: 南山小学校校歌\nM: 4/4\nL: 1/8\nQ: 1/4=115\nK: Bb\n[V: Top clef=treble-8 name="安奈" snm="安"]\nF2||:B3cd2B2|F4D2 G3/2A1/2|B3cB2G2|F6B2|\nw:あ ざ ぶ の お か に そ び え て た て る こ\nw:* な み の や ま の か が や く れ き し ほ\n[V: 2nd clef=treble-8 name="明日香" snm="明"]\nz2||:d8|d8|d4c4|c4d4|\n[V: 3rd clef=treble-8 name="諒悟" snm="諒"]\nz2||:c8|B8|B4A4|A4B4|\n[V: 4th clef=treble-8 name="治城" snm="治"]\nz2||:F8|F8|G4F4|F4F4|\n[V: 5th clef=bass name="圭太" snm="圭"]\nz2||:B,,8|D,8|E,4 E,4|D,4 G,,4|\n[V: Top]\nG3cB2D2|F3GF2 B3/2B1/2|F3DD2C2|B,6C2||\nw:う しゃ を め ぐ ー る き ぎ の わ か め の し\nw:し ー の き しょう ー の そ ら す み わ た る は\n[V: 2nd]\nd4c4|c4d4|e4=f4|e8||\n[V: 3rd]\nB4A4|A4B4|B4B4|B8||\n[V: 4th]\nG4F4|F4F4|G4G4|G8||\n[V: 5th]\nE,4 E,4|D,4 G,,4|C,4 F,,4|B,,8||\n[V: Top]\nC3C CF2E|D2F2z2B3/2A1/2|G3GG2c2|c6 d3/2c1/2|\nw:じ に の び ー ゆ く わ れ ら が す が た お お\nw:て な き ー そ ら は わ れ ら が こ こ ろ お お\n[V: 2nd]\nd4c4|c4d4|e4e4|e8||\n[V: 3rd]\nB4A4|A4B4|B4B4|B8||\n[V: 4th]\nG4F4|F4F4|G4G4|G8||\n[V: 5th]\nE,4 E,4|D,4 G,,4|C,4 =E,,4|F,,8||\n[V: Top]\nB3B cB2G|F6 B3/2B1/2|F3D D2C2|B,6 z2||\nw:す く す く ー と の び ゆ く す が た\nw:ひ ろ び ろ ー と は て な き こ こ ろ\n[V: 2nd]\nd4c4|c4d4|e4=f4|e8||\n[V: 3rd]\nB4A4|A4B4|B4B4|B8||\n[V: 4th]\nG4F4|F4F4|G4G4|G8||\n[V: 5th]\nE,4 E,4|D,4 G,,4|C,4 F,,4|B,,8||\n[V: Top]\nF3/2G1/2 FD FB2c|d6 G3/2G1/2|F3d c2c2|B6 F2:|]\nw:た の し く ま な ー ぶ わ れ ら は こ こ に み\nw:む つ み て は げ ー む わ れ ら は こ こ に *\n[V: 2nd]\nd8|d8|d4e4|d8:|]\n[V: 3rd]\nB8|B8|B4c4|B8:|]\n[V: 4th]\nF8|F8|F4A4|F8:|]\n[V: 5th]\nB,,8|z1 B,,2C,1D,4|B,,4 F,,4|B,,8:|]\n'
    };
  }
};
</script>

<style>
.hello {
  text-align: left;
}
#abc-source {
  width: 350px;
  height: 300px;
}

pre {
  border: 1px solid #888888;
  padding: 6px;
  border-radius: 4px;
  width: 350px;
}
</style>
