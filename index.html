<form method="POST">
  <table width="500" cellspacing="0" cellpadding="3" border="0" align="center">
    <tbody><tr> 
      <td align="right">Password length:</td>
      <td> 
        <input type="text" id="len" size="6" value="5" data-cip-id="len"></td>
    </tr>
    <tr> 
      <td align="right">Speed:</td>
      <td> 
        <input type="text" id="speed" size="11" value="500,000" name="T1" data-cip-id="speed"> passwords per second</td>
    </tr>
    <tr> 
      <td height="25" align="right">Number of computers: </td>
      <td> 
        <input type="text" id="pcn" size="6" value="1" name="T2" data-cip-id="pcn"></td>
    </tr>
    <tr align="center"> 
      <td colspan="2" height="12"> 
        <table width="400" cellspacing="0" cellpadding="3" border="0">
          <tbody><tr> 
            <td width="25"> <input type="checkbox" name="cslwr" value="ON" checked=""></td>
            <td>chars in lower case&nbsp;</td>
            <td width="25"> <input type="checkbox" name="cssymb" value="ON"></td>
            <td>common punctuation&nbsp;</td>
          </tr>
          <tr> 
            <td width="25"> <input type="checkbox" name="csuppr" value="ON"></td>
            <td>chars in upper case</td>
            <td width="25"> <input type="checkbox" name="csascii" value="ON"></td>
            <td>full ASCII</td>
          </tr>
          <tr> 
            <td width="25" height="25"> 
              <input type="checkbox" name="csdigits" value="ON"></td>
            <td colspan="3">digits&nbsp;</td>
          </tr>
        </tbody></table></td>
    </tr>
    <tr align="center"> 
      <td colspan="2" height="5"> 
        <input type="button" value="Calculate!" onclick="doit();"></td>
    </tr>
    <tr bgcolor="gray" align="center"> 
      <td colspan="2" height="6">Brute Force Attack 
        will take up to <strong><span id="result2"> a minute</span></strong></td>
    </tr>
  </tbody></table>
</form>
<script>
function doit() {
    var n = parseInt(document.all.item("len").value);
    var speedS = document.all.item("speed").value;
    speedS = speedS.replace(",", "");
    var speed = parseFloat(speedS);
    var pcn = parseInt(document.all.item("pcn").value);
    var cslen = 0;
    if (document.all.item("cslwr").checked)
        cslen += 26;
    if (document.all.item("csuppr").checked)
        cslen += 26;
    if (document.all.item("csdigits").checked)
        cslen += 10;
    if (document.all.item("cssymb").checked)
        cslen += 12;
    if (document.all.item("csascii").checked)
        cslen = 188;

    var t = Math.pow(cslen, n) / speed / pcn;
    var s;
    console.log(t)
    if (t < 60)
        s = " a minute";
    else {
        t /= 60;
        if (t < 180)
            s = Math.ceil(t).toString() + " minutes";
        else {
            t /= 60;
            if (t < 72)
                s = Math.ceil(t).toString() + " hours";
            else {
                t /= 24;
                if (t < 90)
                    s = Math.ceil(t).toString() + " days";

                else {
                    t /= 30;
                    if (t < 36)
                        s = Math.ceil(t).toString() + " months";
                    else {
                        t /= 12;
                        s = Math.ceil(t).toString() + " years";
                    }
                }

            }
        }
    }


    document.all.item("result2").innerHTML = s;
}
</script>
