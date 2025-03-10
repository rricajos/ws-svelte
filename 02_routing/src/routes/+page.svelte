
<h1>Home</h1>
<div>
  <a href="/" class="active">Home</a>
  <a href="/products">Products</a>
  <a href="/subscriptions">Subscriptions</a>
</div>


<style>
  :global(body) {
    box-sizing: border-box;
    height: 100vh;
    margin: 0;
    background-color: #f00;
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: center;
    align-content: center;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  :global(div) {
    padding: 2rem;
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    align-content: center;
    justify-content: center;
    align-items: center;
  }
  :global(a) {
    margin: 0.75rem;
    text-decoration: underline;
    text-underline-offset: 8px;
    color: rgb(239, 222, 255);
    font-size: 2rem;
    text-shadow: 0px 0px 10px black;
  }
  :global(a:hover), :global(a.active) {
    filter: brightness(120%);
    text-shadow: 0px 0px 20px black;
    text-underline-offset: 12px;
  }

	:global(h1), :global(h2){
   
    font-size: 3rem;
    box-sizing: border-box;
    
		width: 100%;
    margin: 0;
		text-align: center;
    color: white;
    text-shadow: 0px 0px 10px black;
	}
</style>
