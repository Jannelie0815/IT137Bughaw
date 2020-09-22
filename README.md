<style>
    html,
body,
#intro{
    height: 100%;
}
#intro{
    background: #152238 no-repeat center center fixed;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
}
form{
    background: #ffffff;
}
.form-container{
    border-radius: 10px;
    padding: 30px;
    box-shadow: 0px 0px 10px 0px;
}
.bg{
    width: 60px;
    height: 75px;
    position: absolute;
    top: -40px;
    left: 42%;
}
</style>

<!doctype html>
<html lang="en">
  <head>
    <title>Jannelie C. Bughaw</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="css/bootstrap.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  </head>

  <body>
    <div id="intro" class="view">
        <div class="full-bg-img">
            <br><br><br><br><br><br><br><br>
            <section class="container-fluid">
                <section class="row justify-content-center">
                    <section class="col-12 col-sm-6 col-md-3">
                        <img src="icon.png" class="bg">
                        <form class="form-container">
                            <h3 class="text-center font-weight-bold">Login Form</h3>
                            <div class="form-group">
                                <label for="exampleInputEmail1">Email address</label>
                                <input type="text" class="form-control" id="exampleInputEmail1" placeholder="Enter email">
                            </div>
                            <div class="form-group">
                                <label for="exampleInputPassword1">Password</label>
                                <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
                            </div>
                            <div class="form-check">
                                <input type="checkbox" class="form-check-input" id="exampleCheck1">
                                <label class="form-check-label" for="exampleCheck1">Remember me</label>
                            </div>
                            <button type="submit" class="btn btn-block btn-primary">Submit</button>
                        </form>
                    </section>
                </section>
            </section>
        </div>
    </div>
  </body>
</html>
