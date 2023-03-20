<script>
  
  import Youtube from "svelte-youtube-embed";
</script>
<!-- <script>
  let player1, player2;
  let player1State, player2State;
  import Youtube from "./Youtube.svelte";
</script>
Simple Youtube Component with props:<br>
<Youtube videoId="hLQl3WQQoQ0" />

<hr>
Compontent with props & Events :<br>
<Youtube
  videoId="M7lc1UVf-VE"
  on:PlayerStateChangeString={({ detail }) =>  player1State = detail}
  bind:this={player1} /><br>
<button on:click={() => player1.play()}>
  play v1
</button><br>
Player 1 State: {player1State}



<br>
<Youtube
  videoId="M7lc1UVf-VE"
  on:PlayerStateChangeString={({ detail }) => player2State = detail}
  bind:this={player2} /><br>
<button on:click={() => player2.play()}>
  play v2
</button><br>
Player 2 State: {player2State} -->
<Youtube id="hLQl3WQQoQ0">
  <button>play</button>
</Youtube>
<iframe width="560" height="315" src="https://www.youtube.com/embed/hLQl3WQQoQ0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
