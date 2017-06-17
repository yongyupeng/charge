# charge
<!DOCTYPE html>
<html lang="zh-TW">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>找零效率化</title>

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" integrity="sha384-rwoIResjU2yc3z8GV/NPeZWAv56rSmLldC3R/AZzGRnGxQQKnKkoFVhFQhNUwEyJ" crossorigin="anonymous">
    <!-- 引入我們自己寫的 CSS -->
    <link rel="stylesheet" href="./css/index.css">
</head>

<body>

    <div class="container">
        <div class="jumbotron">
            <h1>找零效率化</h1>
        </div>

        <div class="form-group row">
            <label for="example-number-input" class="col-2 col-form-label">cost($)</label>
            <div class="col-10">
                <input class="form-control" type="number" value="480" id="cost">
            </div>
        </div>

        <div class="form-group row">
            <label for="example-number-input" class="col-2 col-form-label">pay($)</label>
            <div class="col-10">
                <input class="form-control" type="number" value="1500" id="pay">
            </div>
        </div>

        <button type="button" class="btn btn-primary">計算</button>

        <div class="form-group row">
            <label for="example-number-input" class="col-2 col-form-label">change($)</label>
            <div class="col-10">
                <input class="form-control" type="number" id="result1">
            </div>
        </div>

        <div class="form-group row">
            <label for="example-number-input" class="col-2 col-form-label">一千元(張)</label>
            <div class="col-10">
                <input class="form-control" type="number" id="result2">
            </div>
        </div>

        <div class="form-group row">
            <label for="example-number-input" class="col-2 col-form-label">五百元(張)</label>
            <div class="col-10">
                <input class="form-control" type="number" id="result3">
            </div>
        </div>

        <div class="form-group row">
            <label for="example-number-input" class="col-2 col-form-label">一百元(張)</label>
            <div class="col-10">
                <input class="form-control" type="number" id="result4">
            </div>
        </div>

        <div class="form-group row">
            <label for="example-number-input" class="col-2 col-form-label">五十元(個)</label>
            <div class="col-10">
                <input class="form-control" type="number" id="result5">
            </div>
        </div>

        <div class="form-group row">
            <label for="example-number-input" class="col-2 col-form-label">十元(個)</label>
            <div class="col-10">
                <input class="form-control" type="number" id="result6">
            </div>
        </div>

        <div class="form-group row">
            <label for="example-number-input" class="col-2 col-form-label">五元(個)</label>
            <div class="col-10">
                <input class="form-control" type="number" id="result7">
            </div>
        </div>

        <div class="form-group row">
            <label for="example-number-input" class="col-2 col-form-label">一元(個)</label>
            <div class="col-10">
                <input class="form-control" type="number" id="result8">
            </div>
        </div>
    </div>



    <!-- jQuery first, then Tether, then Bootstrap JS. -->
    <script src="https://code.jquery.com/jquery-3.1.1.slim.min.js" integrity="sha384-A7FZj7v+d/sdmMqp/nOQwliLvUsJfDHW+k9Omg/a/EheAdgtzNs3hpfag6Ed950n" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.min.js" integrity="sha384-DztdAPBWPRXSA/3eYEEUWrWCy7G5KFbe8fFjk5JAIxUYHKkDx6Qin1DkWx51bBrb" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js" integrity="sha384-vBWWzlZJ8ea9aCX4pEW3rVHjgjt7zpkNpZk+02D9phzyeVkE+jo0ieGizqPLForn" crossorigin="anonymous"></script>

    <!-- 引入我們自己寫的 JavaScript -->
    <script src="./js/index.js"></script>
</body>

</html>
