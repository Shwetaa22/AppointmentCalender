# AppointmentCalender
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Appointment Calender</title>
<link rel="icon" href="data:;base64,=">
<link href="bootstrap-3.3.7-dist\css\bootstrap.min.css" rel="stylesheet"> 
<script src="bootstrap-3.3.7-dist\js\bootstrap.min.js"></script>  
<script src="bootstrap-3.3.7-dist\js\jquery-3.1.1.slim.min.js"></script>
<style type="text/css">
  table {
    
    border-spacing: 0;
    width: 100%;
   
}
 td 
    {
    text-align: left;
    padding: 8px;
     
   
    }
/*tr:nth-child(even)
    {
        background-color: azure;
    }
    tr*/ 
.btn
    {
    border-radius: 50%;
    
    }
   hd
    {
        
    }
</style>
  <script >
      function addAppointment(id)
      {
        var txt;
        var id="d"+id;
        var appo = prompt("Schedule the appointment");
    if (appo == null || appo == "") {
        txt = "";
    } else {
        txt = "Appointment:\n"+ appo ;
    }
          
    document.getElementById(id).innerHTML =  txt;
        
      }
</script>  
</head>
<body>
<div>
    <div class="hd" >
    <h1><b><i><center>Appointment Calender&nbsp;&nbsp;<span class="glyphicon glyphicon-user"></span></center></i></b></h1>
        </div>
    <br>
     <div class="">
    <table class="table table-bordered" "table-responsive">
      <thead style="background-color: aliceblue">
          <tr >
            <th style="text-align: left">Time-Slots</th>
            <th style="text-align: left">Monday</th>
            <th style="text-align: left">Tuesday</th>
            <th style="text-align: left">Wednesday</th>
            <th style="text-align: left">Thursday</th>
            <th style="text-align: left">Friday</th>
            <th style="text-align: left">Saturday</th>
            <th style="text-align: left">Sunday</th>
          </tr>
        </thead> 
        <tbody>
        <tr class="success">
        <td style="text-align: left;width:140px">12.00 AM -1.00 PM</td>
        <td id="m1">
        <div id="dm1" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap:break-word"><button type="button" id="m1" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t1">
        <div id="dt1" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t1" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w1">
        <div id="dw1" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="w1" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th1">
        <div id="dth1" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th1" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f1">
        <div id="df1" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f1" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s1">
        <div id="ds1" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s1" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su1">
        <div id="dsu1" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su1" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>    
        </tr>
        <tr class="active">
        <td style="text-align: left">1.00 PM -2.00 PM</td>
        <td id="m2">
        <div id="dm2" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="m2" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t2">
        <div id="dt2" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t2" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w2">
        <div id="dw2" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="w2" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th2">
        <div id="dth2" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th2" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f2">
        <div id="df2" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f2" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s2">
        <div id="ds2" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s2" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su2">
        <div id="dsu2" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su2" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>        
        </tr>
        <tr class="info">
        <td style="text-align: left">2.00 PM -3.00 PM</td>
            <td id="m3">
        <div id="dm3" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="m3" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t3">
        <div id="dt3" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t3" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w3">
        <div id="dw3"style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="w3" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th3">
        <div id="dth3" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th3" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f3">
        <div id="df3" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f3" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s3">
        <div id="ds3" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s3" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su3">
        <div id="dsu3" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su3" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>    
        </tr>
        <tr class="warning">
        <td style="text-align: left">3.00 PM -4.00 PM</td>
         <td id="m4">
        <div id="dm4" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="m4" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t4">
        <div id="dt4" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t4" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w4">
        <div id="dw4" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="w4" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th4">
        <div id="dth4" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th4" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f4">
        <div id="df4" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f4" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s4">
        <div id="ds4" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s4" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su4">
        <div id="dsu4" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su4" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>      
            
        </tr>
        <tr class="danger">
        <td style="text-align: left">4.00 PM -5.00 PM</td>
            <td id="m5">
        <div id="dm5" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="m5" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t5">
        <div id="dt5" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t5" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w5">
        <div id="dw5" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="w5" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th5">
        <div id="dth5" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th5" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f5">
        <div id="df5" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f5" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s5">
        <div id="ds5" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s5" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su5">
        <div id="dsu5" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su5" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>    
        </tr>
        <tr class="success">
        <td style="text-align: left">5.00 PM -6.00 PM</td>
            <td id="m6">
        <div id="dm6" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="m6" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t6">
        <div id="dt6" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t6" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w6">
        <div id="dw6" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="w6" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th6">
        <div id="dth6" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th6" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f6">
        <div id="df6"  style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f6" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s6">
        <div id="ds6" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s6" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su6">
        <div id="dsu6" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su6" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
        </tr>
        <tr class="active">
        <td style="text-align: left">6.00 PM -7.00 PM</td>
        <td id="m7">
        <div id="dm7" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="m7" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t7">
        <div id="dt7" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t7" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w7">
        <div id="dw7" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="w7" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th7">
        <div id="dth7" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th7" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f7">
        <div id="df7" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f7" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s7">
        <div id="ds7" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s7" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su7">
        <div id="dsu7" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su7" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
        </tr>
        <tr class="info">
        <td style="text-align: left">7.00 PM -8.00 PM</td>
            <td id="m8">
        <div id="dm8" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="m8" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t8">
        <div id="dt8" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t8" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w8">
        <div id="dw8" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap:normal"><button type="button" id="w8" class="btn btn-info" onclick="addAppointment(this.id)"><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th8">
        <div id="dth8" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th8" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f8">
        <div id="df8" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f8" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s8">
        <div id="ds8" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s8" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su8">
        <div id="dsu8" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su8" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
        </tr>
        <tr class="warning">
        <td style="text-align: left">8.00 PM -9.00 PM</td>
        <td id="m9">
        <div id="dm9" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="m9" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t9">
        <div id="dt9" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t9" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w9">
        <div id="dw9" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="w9" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th9">
        <div id="dth9" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th9" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f9">
        <div id="df9" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f9" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s9">
        <div id="ds9" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s9" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su9">
        <div id="dsu9" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su9" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
        </tr>
        <tr class="danger">
        <td style="text-align: left">9.00 PM -10.00 PM</td>
        <td id="m10">
        <div id="dm10" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="m10" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t10">
        <div id="dt10" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t10" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w10">
        <div id="dw10" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="w10" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th10">
        <div id="dth10" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th10" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f10">
        <div id="df10" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f10" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s10">
        <div id="ds10" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s10" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su10">
        <div id="dsu10" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su10" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
        </tr>
        <tr class="info">
        <td >10.00 PM -11.00 PM</td>
                <td id="m11">
        <div id="dm11" style="width:70px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="m11" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
         <td id="t11">
        <div id="dt11" style="width:70px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="t11" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="w11">
        <div id="dw11" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="w11" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="th11">
        <div id="dth11" style="width:60px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="th11" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="f11">
        <div id="df11" style="width:60px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="f11" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="s11">
        <div id="ds11" style="width:30px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="s11" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
            <td id="su11">
        <div id="dsu11" style="width:60px;display: inline-block">Appointment:</div>
        <div style="text-align:right;margin-top:-18px;word-wrap: normal"><button type="button" id="su11" class="btn btn-info" onclick="addAppointment(this.id)" ><span class="glyphicon glyphicon-plus-sign"></span></button></div>
        </td>
        </tr>
        </tbody>
    </table>
        </div>
</div>        
</body>
</html>
