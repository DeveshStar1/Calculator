<!DOCTYPE html>
<html>
<head>
<title>
    Tip Calculator
    </title>
    <link rel="stylesheet" type="text/css" href="normalize.css">
    <link rel="stylesheet" type="text/css" href="style.css">

</head>
<body>
<div id="container">
    <h1>Tip Calculator</h1>
    <div id="calculator">
    <form>
        <label>
        How Much Was Bill?<br>&#8377;
            <input type="text" id="billAmount">
        </label>
        <label>
            How Was Service Dear?<br>
            <select id="serviceQuality">
                <option disabled selected value="0">--choose option--></option>
            <option value="0.3">30%-Outstanding</option>
                <option value="0.2">20%-Good Service</option>
                <option value="0.1">10%-Bad Service</option>
                <option value="0.05">5%-Terrific</option>
     </select>
</label>
<label>
    Kitne Log Dildaar Hai?<br>
    <input type="text" id="totalPeople">People
</label>
        <button type="button" id="calculate">Calculate!</button>
        </form>
    </div><!-- calculator ends-->
        <div id="totalTip">
        <sup>&#8377;</sup><span id="tip">0.00</span>
            <small id="each">Each</small>
        
        
        </div>
    </div><!-- Container end-->
    <script type="text/javascript" src="scriptc.js"></script>
    </body>
    </html>

