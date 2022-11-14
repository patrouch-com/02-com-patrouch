<svelte:head>
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Changa">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Hurricane&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Special+Elite&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Hurricane&family=Inspiration&display=swap" rel="stylesheet">
<link rel="preload" href="https://fonts.gstatic.com/s/quicksand/v7/6xKtdSZaM9iE8KbpRA_hK1QNYuDyPw.woff2" as="font" crossorigin>
<link rel="preload" href="https://fonts.gstatic.com/s/lato/v14/S6uyw4BMUTPHjx4wXiWtFCc.woff2" as="font" crossorigin>
</svelte:head>

<script lang='ts'>
import MastodonLogo from '/src/images/mastodon-logo.svg';
</script>

<h1>PATROUCH . COM</h1> 
<p>This domain is for the extended, far-flung, united or estranged members of Patrouch clan. If your last name or that of an ancestor of yours is or ever was Patrouch and you'd like you're own subdomain, let me know and I'll set you up.</p><br>
<h3>Reach me on Mastodon at</h3>
<h2>@mxurbano@mastodon.mexicanbold.com</h2>

<div class="corner">

<a href="https://mastodonte.red" target="_blank" rel="noopener noreferrer">
<img src={MastodonLogo} alt="Red Mastodon Logo">
</a>
</div>


<style>


.corner {
		width: 3em;
		height: 3em;
	}

.corner a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}

.corner img {
		width: 2em;
		height: 2em;
		object-fit: contain;
	}

a:hover {
		color: red;
	}

h1 {
background: #FFF488;
border-radius: 1.5em;
padding: 2.75em;
position: absolute;
left: 50%;
margin-right: -50%;
transform: translate(-50%, -50%); 
font-size: 3em;
  font-family: "Special Elite";
  color: teal;
  text-align: center;
  }

h2 {
  background: black;
  border-radius: 1em;
  padding: 1em;
  position: absolute;
  top: 25%;
  left: 50%;
  margin-right: -50%;
  transform: translate(-50%, -50%);
  color: pink;
  font-size: 2rem; 
  text-align: center;
}

h3 {
  background: teal;
  border-radius: 1em;
  padding: 1.75em;
  position: absolute;
  top: 15%;
  left: 50%;
  margin-right: -50%;
  transform: translate(-50%, -50%);
  color: white;
  font-size: 2rem; 
  text-align: center;
}
p {
  background: pink;
  border-radius: 2em;
  padding: 4em;
  text-align: center;
  font-family: verdana;
  color: black;
  font-size: 1.5em;
position: absolute;
        top: 50%;
        left: 50%;
        margin-right: -50%;
        transform: translate(-50%, -50%) 
}
</style>
