<!DOCTYPE html>
<html lang="jp">

<head>
    <meta charset="utf-8" />

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <link href="./style.css" rel="stylesheet" />

    <title>Othello</title>
</head>

<body>
    <div class="container">
        <div id="title">
            <h1>Othello</h1>
        </div>
        <div id="board">
            <div class="board-row">
                <button type="button" class="btn btn-outline-dark square" data-row="0" data-col="0"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="0" data-col="1"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="0" data-col="2"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="0" data-col="3"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="0" data-col="4"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="0" data-col="5"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="0" data-col="6"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="0" data-col="7"></button>
            </div>
            <div class="board-row">
                <button type="button" class="btn btn-outline-dark square" data-row="1" data-col="0"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="1" data-col="1"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="1" data-col="2"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="1" data-col="3"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="1" data-col="4"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="1" data-col="5"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="1" data-col="6"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="1" data-col="7"></button>
            </div>
            <div class="board-row">
                <button type="button" class="btn btn-outline-dark square" data-row="2" data-col="0"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="2" data-col="1"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="2" data-col="2"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="2" data-col="3"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="2" data-col="4"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="2" data-col="5"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="2" data-col="6"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="2" data-col="7"></button>
            </div>
            <div class="board-row">
                <button type="button" class="btn btn-outline-dark square" data-row="3" data-col="0"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="3" data-col="1"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="3" data-col="2"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="3" data-col="3"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="3" data-col="4"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="3" data-col="5"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="3" data-col="6"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="3" data-col="7"></button>
            </div>
            <div class="board-row">
                <button type="button" class="btn btn-outline-dark square" data-row="4" data-col="0"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="4" data-col="1"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="4" data-col="2"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="4" data-col="3"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="4" data-col="4"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="4" data-col="5"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="4" data-col="6"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="4" data-col="7"></button>
            </div>
            <div class="board-row">
                <button type="button" class="btn btn-outline-dark square" data-row="5" data-col="0"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="5" data-col="1"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="5" data-col="2"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="5" data-col="3"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="5" data-col="4"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="5" data-col="5"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="5" data-col="6"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="5" data-col="7"></button>
            </div>
            <div class="board-row">
                <button type="button" class="btn btn-outline-dark square" data-row="6" data-col="0"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="6" data-col="1"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="6" data-col="2"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="6" data-col="3"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="6" data-col="4"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="6" data-col="5"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="6" data-col="6"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="6" data-col="7"></button>
            </div>
            <div class="board-row">
                <button type="button" class="btn btn-outline-dark square" data-row="7" data-col="0"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="7" data-col="1"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="7" data-col="2"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="7" data-col="3"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="7" data-col="4"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="7" data-col="5"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="7" data-col="6"></button>
                <button type="button" class="btn btn-outline-dark square" data-row="7" data-col="7"></button>
            </div>
        </div>
        <div id="controller">
            <button type="button" id="btn-initialize" class="btn btn-secondary">リセット</button>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <script
    src="https://code.jquery.com/jquery-3.6.0.min.js"
    integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4="
    crossorigin="anonymous"
    ></script>

    <script src="./script.js"></script>
</body>

</html>
