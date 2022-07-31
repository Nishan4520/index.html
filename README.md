<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>www.Nishanregmi.com</title>
    <link rel="stylesheet" href="./styles.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
          <script>
  
         function dis(val)
         {
             document.getElementById("result").value+=val
         }
           
         
         function solve()
         {
             let x = document.getElementById("result").value
             let y = eval(x)
             document.getElementById("result").value = 
         }
           
        
         function clr()
         {
             document.getElementById("result").value = ""
         }

         function temperatureConverter(valNum) {
  valNum = parseFloat(valNum);
  document.getElementById("outputCelsius").innerHTML = (valNum-32) / 1.8;
}
      </script>
       <style>
         .title{
         margin-bottom: 10px;
         text-align:center;
         width: 210px;
         color:green;
         border: solid black 2px;
         }
  
         input[type="button"]
         {
         background-color:;
         color:green;
         border: solid black 2px;
         width:100%
         }
  
         input[type="text"]
         {
         background-color:white;
         border: solid black 2px;
         width:100%
         }

        
    
         
         
         }
      </style>

<body>
  <header> <h1>WELCOME TO THE OFFICIAL WEBSITE OF NISHAN REGMI</h1>
</header>
<div class="navbar">
<a class="active" href="#"><i class="fa fa-fw fa-home"></i> Home</a>
  <a href="#"><i class="fa fa-fw fa-search"></i> Search</a>
  <a href="#"><i class="fa fa-fw fa-envelope"></i> Contact</a>
  <a href="#"><i class="fa fa-fw fa-user"></i> Login</a>
</div>
<section>
    <div class="row"></div>
<div class="column"><h2>what is computer?</h2><h3>A computer is a programmable device that stores, retrieves, and processes data. The term "computer" was originally given to humans (human computers) who performed numerical calculations using mechanical calculators, such as the abacus and slide rule. The term was later given to mechanical devices as they began replacing human computers. Today's computers are electronic devices that accept data (input), process that data, produce output, and store (storage) the results (IPOS).</h3>
<div class="column"><h2>What are the types of computer?</h2> <H3>
    Depending upon the internal structure and subsequent features and applicability, computer system is categorized as follows:
</section> <ul>
       <li>micro computer</li>
       <li>milli computer</li>
       <li>mainframe computer</li>
       <li>super computer</li>
    </ul>
<h1>micro computer</h1>
<p>A microcomputer is a complete computer on a small scale, designed for use by one person at a time. An antiquated term, a microcomputer is now primarily called a personal computer (PC), or a device based on a single-chip microprocessor. Common microcomputers include laptops and desktops. Beyond standard PCs, microcomputers also include some calculators, mobile phones, notebooks, workstations and embedded systems.</p>
<h1>milli computer</h1>
<p>minicomputer, computer that was smaller, less expensive, and less powerful than a mainframe or supercomputer but more expensive and more powerful than a personal computer. Minicomputers were used for scientific and engineering computations, business transaction processing, file handling, and database management. Minicomputers as a distinct class of computers emerged in the late 1950s and reached their peak in the 1960s and ’70s before declining in popularity in the 1980s and ’90s. Their niche was filled by more powerful personal computers, workstations, and small or midsize servers.</p>
<h1>mainframe computer</h1>
<p>Mainframes are a type of computer that generally are known for their large size, amount of storage, processing power and high level of reliability. They are primarily used by large organizations for mission-critical applications requiring high volumes of data processing. In general, there are a few characteristics of mainframes that are common among all mainframe vendors: Nearly all mainframes have the ability to run (or host) multiple operating systems. Mainframes can add or hot swap system capacity without disruption. Mainframes are designed to handle very high volume input and output (I/O) and emphasize throughput computing. A single mainframe can replace dozens or even hundreds of smaller servers</p>
<h1>super computer</h1>
<p>supercomputer, any of a class of extremely powerful computers. The term is commonly applied to the fastest high-performance systems available at any given time. Such computers have been used primarily for scientific and engineering work requiring exceedingly high-speed computations. Common applications for supercomputers include testing mathematical models for complex physical phenomena or designs, such as climate and weather, evolution of the cosmos, nuclear weapons and reactors, new chemical compounds (especially for pharmaceutical purposes), and cryptology. As the cost of supercomputing declined in the 1990s, more businesses began to use supercomputers for market research and other business-related models.</p>
<h1>calculator</h1>

<table border="1" size="100px">
         <tr>
            <td colspan="3"><input type="text" id="result"/></td>
            <!-- clr() function will call clr to clear all value -->
            <td><input type="button" value="c" onclick="clr()"/> </td>
         </tr>
         <tr>
            <!-- create button and assign value to each button -->
            <!-- dis("1") will call function dis to display value -->
            <td><input type="button" value="1" onclick="dis('1')"/> </td>
            <td><input type="button" value="2" onclick="dis('2')"/> </td>
            <td><input type="button" value="3" onclick="dis('3')"/> </td>
            <td><input type="button" value="/" onclick="dis('/')"/> </td>
         </tr>
         <tr>
            <td><input type="button" value="4" onclick="dis('4')"/> </td>
            <td><input type="button" value="5" onclick="dis('5')"/> </td>
            <td><input type="button" value="6" onclick="dis('6')"/> </td>
            <td><input type="button" value="-" onclick="dis('-')"/> </td>
         </tr>
         <tr>
            <td><input type="button" value="7" onclick="dis('7')"/> </td>
            <td><input type="button" value="8" onclick="dis('8')"/> </td>
            <td><input type="button" value="9" onclick="dis('9')"/> </td>
            <td><input type="button" value="+" onclick="dis('+')"/> </td>
         </tr>
         <tr>
            <td><input type="button" value="." onclick="dis('.')"/> </td>
            <td><input type="button" value="0" onclick="dis('0')"/> </td>
          
            <td><input type="button" value="=" onclick="solve()"/> </td>
            <td><input type="button" value="*" onclick="dis('*')"/> </td>
         </tr>
</table>
    


<form>
  <h1>Register Form</h1>
  <div class="input-container">
    <i class="fa fa-user icon"></i>
    <input class="input-field" type="text" placeholder="Username" name="usrnm">
  </div>

  <div class="input-container">
    <i class="fa fa-envelope icon"></i>
    <input class="input-field" type="text" placeholder="Email" name="email">
  </div>

  <div class="input-container">
    <i class="fa fa-key icon"></i>
    <input class="input-field" type="password" placeholder="Password" name="psw">
  </div>

  <button type="submit" class="btn">Register</button>
</form>

</body>
</html>
