<script>
    import Typewriter from 'svelte-typewriter'
</script>

<div class = "title">
    <Typewriter interval=45>
        <h1>Sajel Surati</h1>
    </Typewriter>
</div>


<div class = "body">
    <img src = "picture.png" alt = "A picture of a woman smiling" class = "picture">
    <p>Hi there! My name is Sajel Surati and I am a senior at Bowdoin College studying
        math and computer science. I'm interested in the intersection of computer science 
        and society. </p>
</div>
<style>
    .title {
        font-size: x-large;
        text-align: center;
        padding-top: 150px;
    }


    .body {
        padding-top: 30px;
        width: 70%;
        display: block;
        margin-left: auto;
        margin-right: auto;
        text-align: center;
    }

    .body img {
        height: 45%;
        width: 45%;
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
</style>