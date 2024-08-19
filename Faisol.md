<style>
  .st1{
    background-color: rgb(61, 181, 61);
}
.nd1{
    font-size: 50px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: aliceblue;
}
.rd1{
    color: aliceblue;
    font-size: 10px;
    font-family: Arial, Helvetica, sans-serif;
}
.th4{
    background-color: rgb(21, 21, 105);
    height: 50px;
    color: white;
    font-size: 30px;
}
input{
    background: transparent;
    border: none;
    border-bottom: 2px transparent;
    color: rgb(16, 17, 18);
    width: 400px;
}
fieldset{
    border-radius: 10px;
}

.th6{
    margin: 20px;
    width: 40%;
    float: right;
    
}
.th5{
    float: left;
    width: 40%;
    margin: 20px;

}


.th7{
    float: left;
    width: 40%;
    margin: 20px;
}
.th8{
    float: right;
    width: 40%;
    margin: 20px;
    cursor: pointer;
}
.mm{
    width: 80%;
    margin: 20px;
}
.th11{
    
        background-color: rgb(21, 21, 105);
        height: 50px;
        color: white;
        font-size: 30px;
}
.th12{
    float: left;
    width: 40%;
    margin: 20px;
}
.th13{
    float: right;
    width: 40%;
    margin: 20px;
}
.th14{
    float: left;
    width: 40%;
    margin: 20px;
}
.th15{
    float: right;
    width: 40%;
    margin: 20px;
    cursor: pointer;
}
.th16{
    width: 100%;
    margin: 20ps;
}
.button{
    padding-left: 1010px;
    
}
.back{
    background-color: snow;
    border-color: aliceblue;
    width: 80px;
    height: 35px;
    cursor: pointer;
}
.submit{
    background-color: rgb(22, 95, 124);
    color: white;
    width: 180px;
     height: 45px;
    cursor: pointer;
}
.faisol{
    box-shadow: 1px 2px 3px 4px rgba(75, 74, 74, 0.3);
    
    height: 770px;
   
    width: 1200px;
    margin: 50px;
}
.hhh{
    width: 
    1000px;
}
.ol{
    width: 1000px;
}
</style>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OLAYEMI</title>
</head>
<link rel="stylesheet" href="2025.css">
<body>
    <DIv class="faisol">
    <div class="st1">
        <div class="nd1">&#9776;    Welcome Hor Lha Yhemhi</div>
        <div class="rd1">Fri Aug 16 2024</div>
    </div>
    <br>
    <hr>
    <br>
    <div class="th4">Parent/Guardian Details</div>
    <form>
        <div class="th5">
        <fieldset>
            <legend>Name:</legend>
            <input type="text">
        </fieldset>
    </div>
    <div class="th6">
        <fieldset>
            <legend>Phone Number:</legend>
            <input type="number">
        </fieldset>
    </div>
    <br> <br><br><br><br>
    <div class="th7">
        <fieldset>
            <legend>E-mail Address:</legend>
            <input type="mail">
        </fieldset>
    </div>
    <div class="th8">
        <fieldset>
            <legend>Relationshp:</legend>
            <div>
                <input list="Relationshp" type="text">
                <datalist id="Relationshp">
                    <option value="Spouse">
                        <option value="Father"> 
                            <option value="Mother"></option>
                            <option value="Sibling"></option>
                </datalist>
            </div>
        </fieldset>
    </div>
    <br> <br><br><br><br>
    <div class="th9">
        <fieldset class="mm">
            <legend>Address:</legend>
            <input class="hhh" type="text">
        </fieldset>
    </div>
    </form>
    <p></p>
    <div class="th11">Next Of Kin</div>
    <form>
        <div class="th12">
        <fieldset>
            <legend>Name:</legend>
            <input type="text">
        </fieldset>
    </div>
    <div class="th13">
        <fieldset>
            <legend>Phone Number:</legend>
            <input type="number">
        </fieldset>
    </div>
    <br><br><br><br><br>
    <div class="th14">
        <fieldset>
            <legend>E-mail Address:</legend>
            <input type="mail">
        </fieldset>
    </div>
    <div class="th15">
        <fieldset>
            <legend>Relationshp with Next of Kin:</legend>
            <div>
                <input list="Relationshp" type="text">
                <datalist id="Relationshp">
                    <option value="Spouse">
                        <option value="Father"> 
                            <option value="Mother"></option>
                            <option value="Sibling"></option>
                </datalist>
            </div>
        </fieldset>
    </div>
    <br> <br><br><br><br>
    <div class="th16">
        <fieldset class="mm">
            <legend>Next of Kin Address:</legend>
            <input class="ol" type="text">
        </fieldset>
    </div>
    </form>
</DIv>

<div class="button"><button class="back">BACK</button> <button class="submit">SAVE & CONTINUE</button></div>

</body>
</html>

