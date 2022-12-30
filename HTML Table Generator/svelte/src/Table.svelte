<script>
let inputRow = 0;
let inputColumn=0;
let inputHeight = 0;
let inputWidth = 0;
let inputPadding = 0;
</script>

<style>
     h3{
        color: rgb(5, 5, 5);
        font-family: 'Inter', sans-serif;
    }
    h5{
        text-align: left;
        margin: 0px;
        color: black;
    }
    input{
        
        background-color: #EEEEEE;
        color: black;
        height: 0.8cm;
        border-radius: 10px;
    }
    div{
        display : flex;
    }
    .A{
        display: flex;
        margin-left: 10px;
        align-items: center;
        justify-content: center;
    }
    .inputs{
        display : flex;
        flex-direction: column;
        margin-right: 10px;
        margin-left: 10px;
        padding: 10px;
        border-radius: 30px;

    }
    .generate{
        background-color: #299C49;
        margin-top: 50px;
    }
    .Reset{
        background-color: #DCF9E4;
        color: black;
        margin-top: 50px;
        margin-left: 10px;
    }

</style>
<head>
    <link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Inter:wght@600&display=swap" rel="stylesheet">
</head>
<main>
    <h3> HTML TABLE GENERATOR</h3>
    
    <div class ="A">
        <div class = "inputs">
            <h5>Rows</h5>
            <input type = "number"bind:value={inputRow}>
        </div>
        <div class = "inputs">
            <h5> Column</h5>
            <input type = "number"bind:value={inputColumn}>
             
        </div>
    </div>
    <div class ="A">
        <div class = "inputs">
            <h5>Height
            </h5>
            <input type = "number"bind:value={inputHeight}>
        </div>
        <div class = "inputs">
            <h5> Width</h5>
            <input type = "number"bind:value={inputWidth}>
             
        </div>
        <div class = "inputs">
            <h5> Padding</h5>
            <input type = "number"bind:value={inputPadding}>
             
        </div>
    </div>
    <div class="A">
        <button class = "generate">
            Generate
        </button>
        <button class = "Reset">
            Reset
        </button>
    </div>
</main>