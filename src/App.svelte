<script>

let one = 0

function add(){
one+=1

}

function added(){
one+=10
}

function less(){
one-=1
}


</script>



<button on:click={add} on:dblclick={added} on:contextmenu|preventDefault={less}>{one}x nuzzles pounces on u uwu u so 
warm </button>


