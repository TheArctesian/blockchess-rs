<div class="body">
    <div class="text">
        <h1>Blockchess</h1>
        <p>Coming late 2023</p>
        <p class="info">
        Track the progress on <a href="https://github.com/thearctesian/blockchess-rs">GitHub</a>
        </p>
    </div>
</div>
<style>
    :global(body){
        margin: 0;
        background-color: #272727; 
    }
    .body{
        color: white;
        height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
    }
    .text{
        background-color: white;
        border-radius: 2rem;
    }
    h1{
        font-size: 10rem;
        font-style: italic;
        margin: 1rem;
    }
    p{
        font-size: 4rem;
        color: black;
        text-align: center;
        margin: 1rem;
    }
    .info{
        margin: 1rem;
        font-size: 2rem;
    }
    h1 {
  --s: 0.1em;   /* the thickness of the line */
  --c: #2c4bff; /* the color */
  
  color: #0000;
  padding-bottom: var(--s);
  background: 
    linear-gradient(90deg,var(--c) 50%,#000 0) calc(100% - var(--_p,0%))/200% 100%,
    linear-gradient(var(--c) 0 0) 0% 100%/var(--_p,0%) var(--s) no-repeat;
  -webkit-background-clip: text,padding-box;
          background-clip: text,padding-box;
  transition: 0.5s;
}
h1:hover {--_p: 100%}
</style>
